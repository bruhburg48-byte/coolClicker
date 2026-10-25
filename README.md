# coolClicker
Auto clicker for daily routine and games.
coolone is an advanced background input automation platform (keyboard and mouse), designed specifically for gamers and users who need to perform repetitive actions in applications without losing focus on their main task.
Unlike simple "clickers," coolone uses complex system methods to simulate input directly into the target window, allowing you to play a game or work in one program while the script controls another.
🚀 Key Features
1. True Background Automation
The program does not require the target window to be active. It uses 5 different input sending methods:

    Foreground Switch: Instantly activates the window for 15ms, sends the command, and returns focus. Ideal for Unity/Unreal Engine games.
    PostMessage: Directly sends system messages to the window without changing its state.
    SendInput / keybd_event: System-level input for maximum compatibility.
    Auto-Diagnostics: The program automatically detects the application type (game, browser, Qt app) and recommends the best method.

2. Advanced Macro Editor

    Visual Timeline: Clear visualization of action sequences.
    Flexible Configuration: Add individual keys, delays, loops, and modifiers (Ctrl, Shift, Alt).
    Preset Library: Ready-made settings for popular games (Minecraft, CS:GO, GTA V) and daily tasks (clipboard, navigation).

3. Smart Window Management

    Process Search: You can bind the script to a process name (e.g., minecraft.exe) rather than a window title (which may change).
    Game Auto-Detection: Scans the system for running game processes upon startup.
    Mass Testing: A feature to test all sending methods at once to choose the most reliable one.

4. Professional Interface & UX

    Multilingual Support: Built-in support for English and Russian with saved preferences.
    Profile System: Save separate configurations for different games or tasks.
    Themes: 5 color schemes (Dark, Blue, Green, Purple, Red).
    Sound Feedback: Notifications for start, stop, and errors.
    Live Statistics: Real-time CPS (actions per second) graph and event log.

🛠 Who is it for?

    Gamers: For auto-jumping, resource farming, opening inventories, or performing routine actions in MMOs/RPGs without minimizing the game.
    Streamers: For managing sound, switching scenes, or sending chat messages during broadcasts.
    Office Workers: For automating routine data entry in background Excel windows or CRM systems.

⚙️ Technical Details

    Security: Does not inject into game processes (no DLL injection) but uses legitimate Windows APIs, reducing the risk of detection by anti-cheat systems (though usage remains the user's responsibility).
    Performance: Optimized Python code using multithreading to ensure the interface does not freeze during heavy macro execution.
    Reliability: Retry system and window reconnection if the target application is restarted.

coolone turns the complex process of configuring bots and macros into a convenient visual tool accessible even to beginners.
