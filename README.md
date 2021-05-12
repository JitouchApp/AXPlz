# AXPlz

Working with macOS's Accessibility API requires the process to be trusted by the operating system. In practice, this means that the user needs to make sure that "Access for assistive devices" is enabled on older versions of macOS, or that the application is enabled in Security > Accessibility preferences.

AXPlz contains code to check if the requirements have been met and AX API is accessible to the program. If not, it displays a helpful, always-on-top reminder on what the user needs to do. On current macOS versions, this looks like this: