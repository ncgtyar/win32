# Win32 API P/Invoke wrappers for C# (.NET Framework)
## A  collection of commonly used Win32 API function imports in C#
- user32.dll
- kernel32.dll
- gdi32.dll
- flags & structs ***(MOUSEEVENTF_..., POINT, RECT, ...)***
- hook delegate

### Basic features:
- Mouse control ***(mouse_event, SetCursorPos, ...)***
- Keyboard input ***(GetAsyncKeyState, RegisterHotKey, ...)***
- Drawing and screen capture ***(BitBlt, CreateCompatibleDC, ...)***
- Window management ***(FindWindow, ShowWindow, ...)***
- Clipboard management ***(OpenClipboard, GetClipboardData, ...)***
- Process hook ***(HookProc)***
