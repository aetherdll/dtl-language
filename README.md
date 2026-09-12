# 📄 DTL (Data Text Language)

**.dtl is a lightweight, minimalist, and easy-to-read data serialization standard.**


📌 Core Rules & Syntax

**File Extension: ⁠.dtl⁠ (File names can be uppercase or lowercase: ⁠settings.dtl⁠, ⁠SERVER.dtl⁠)**

**Keys & Blocks: All keys and block names must be in UPPERCASE (⁠SYSTEM⁠, ⁠PORT⁠, ⁠STATUS⁠).**

**Block Structure: No curly braces ⁠{}⁠. Blocks are defined using ⁠[⁠ and ⁠]⁠.**

**String Values: Purely alphabetical strings must be enclosed in double quotes (⁠"Active"⁠, ⁠"TR-101"⁠).**

**Numbers & Codes:  Pure numbers are written without quotes (⁠8080⁠, ⁠100⁠).   Alphanumeric custom codes/IDs are written without quotes (⁠XYZ999⁠, ⁠CODE10⁠).**

**Comments: Comments are enclosed between ⁠\⁠ symbols (⁠\ This is a comment \⁠).**

📝 Example ⁠.dtl⁠ File:

```bash
\ Server Configuration File \

DATABASE [
  STATUS = "Active",
  PORT = 5432,
  CONNECTION_CODE = DB99XX,
  BACKUP [
    AUTOMATIC = "Yes",
    INTERVAL_DAYS = 7
  ]
]