--========================================================--
--   C00L Key System - Pure Lua (One File)
--   Features:
--     • Username/password login
--     • Key generator (numeric + hex)
--     • Key validator
--     • Key storage in memory
--========================================================--

local USERNAME = "admin"
local PASSWORD = "1234"

local generatedKeys = {}   -- stores keys

--========================================================--
--   Helper: generate numeric key   (XXXX-XXXX-XXXX-XXXX)
--========================================================--
local function generateNumericKey()
    local key = ""
    for g = 1, 4 do
        local seg = ""
        for i = 1, 4 do
            seg = seg .. tostring(math.random(0, 9))
        end
        key = key .. seg .. (g < 4 and "-" or "")
    end
    return key
end

--========================================================--
--   Helper: generate 52-char hex key
--========================================================--
local function generateHexKey()
    local chars = "abcdef0123456789"
    local key = ""
    for i = 1, 52 do
        local rand = math.random(1, #chars)
        key = key .. chars:sub(rand, rand)
    end
    return key
end

--========================================================--
--   Key Validator
--========================================================--
local function validateKey(key)
    for _, k in ipairs(generatedKeys) do
        if k == key then
            return true
        end
    end
    return false
end

--========================================================--
--   Dashboard Menu
--========================================================--
local function dashboard()
    while true do
        print("\n===== C00L LUA KEY SYSTEM =====")
        print("1) Generate Numeric Key")
        print("2) Generate Hex Key (52 chars)")
        print("3) Validate Key")
        print("4) Show All Keys")
        print("5) Exit")
        io.write("Select option: ")

        local choice = io.read()

        if choice == "1" then
            local key = generateNumericKey()
            table.insert(generatedKeys, key)
            print("Generated Numeric Key: " .. key)

        elseif choice == "2" then
            local key = generateHexKey()
            table.insert(generatedKeys, key)
            print("Generated Hex Key: " .. key)

        elseif choice == "3" then
            io.write("Enter key to validate: ")
            local key = io.read()
            if validateKey(key) then
                print("VALID ✓")
            else
                print("INVALID ✗")
            end

        elseif choice == "4" then
            print("\nSaved Keys:")
            for _, k in ipairs(generatedKeys) do
                print(" - " .. k)
            end

        elseif choice == "5" then
            print("Goodbye!")
            break

        else
            print("Invalid option.")
        end
    end
end

--========================================================--
--   Login System
--========================================================--
local function login()
    print("===== LOGIN =====")
    io.write("Username: ")
    local u = io.read()

    io.write("Password: ")
    local p = io.read()

    if u == USERNAME and p == PASSWORD then
        print("\nLogin success!\n")
        dashboard()
    else
        print("Invalid login. Try again.")
    end
end

-- Start program
login()
