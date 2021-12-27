# Mailspring Gruvbox Theme

A useable gruvbox theme for Mailspring that properly inverts colors for light emails without the text becoming unreadable.


When modifying, open developer console and use these commands to test changes:

   ```
   AppEnv.themes.setActiveTheme('ui-light');
   AppEnv.themes.setActiveTheme('your-theme-name');
   ```
# File tree


```
.
├── styles                 # All stylesheets
|   ├── email-frame.less   # Inverts email frame colors properly.
│   ├── ui-variables.less  # UI variables that override N1's defaults
├── package.json           # Metadata about the theme
├── LICENSE.md             # License with usage rights
└── README.md              # Info about your theme and how to use it
```
