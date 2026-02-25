# nvidia-gpu-monitor
A sleek Qt6 desktop widget for monitoring NVIDIA GPU performance on KDE Plasma.
Initial Release

FEATURES:

    Real-time GPU monitoring with 10-second refresh interval
    Radial temperature gauge with color-coded display (green/yellow/red)
    Radial fan speed gauge with cyan-to-purple color scheme
    Linear power consumption gauge (blue to red, 0W to max TDP)
    Linear memory usage gauge (green to red)
    2x2 info grid displaying:
        GPU Utilization percentage
        Performance State (P0, P1, etc.)
        PCI Bus ID
        Compute Mode
    Driver and CUDA version display in footer

USER INTERFACE:

    Dark glossy theme with gradient background
    Customizable GPU image display
    Clean, modern design with NVIDIA green accents

SYSTEM TRAY INTEGRATION:

    Tray icon shows temperature with color-coded arc
    Left-click to show/hide main window
    Right-click context menu (Show Monitor / Quit)
    Tooltip displays temperature and utilization
    Close button minimizes to tray instead of quitting

KDE INTEGRATION:

    Desktop entry for application menu
    Autostart support for KDE Plasma
    Custom application icon

INSTALLATION:

    Simple install.sh script for easy setup
    Portable - can run from any directory
    No root required for user installation

REQUIREMENTS:

    Linux with NVIDIA GPU
    NVIDIA drivers (nvidia-smi)
    Qt6 Widgets
    CMake 3.16+
