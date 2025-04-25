ColorChat Plugin
A simple Minecraft plugin that allows players to use color codes in chat messages. Without Essentials plugin installed!
Features

Players with the appropriate permission can use color codes in their chat messages
Support for all Minecraft color codes and formatting codes
Simple configuration
Admin commands to control the plugin

Installation

Download the plugin JAR file
Place the JAR file in your server's plugins folder
Restart your server or use a plugin manager to load the plugin
Configure permissions as needed

Usage
For Players
If you have the colorchat.use permission, you can use color codes in your chat messages.
Simply type the & character followed by a color code to add colors to your message.
For example:
Hello &aworld&r! This is a &bcolored &cmessage&r!
will appear as:
Hello <span style="color:green">world</span>! This is a <span style="color:aqua">colored</span> <span style="color:red">message</span>!
Color Codes

&0: Black
&1: Dark Blue
&2: Dark Green
&3: Dark Aqua
&4: Dark Red
&5: Dark Purple
&6: Gold
&7: Gray
&8: Dark Gray
&9: Blue
&a: Green
&b: Aqua
&c: Red
&d: Light Purple
&e: Yellow
&f: White

Formatting Codes

&k: Obfuscated (Magic)
&l: Bold
&m: Strikethrough
&n: Underline
&o: Italic
&r: Reset

Commands

/colorchat or /cc: Shows information about the plugin and available color codes
/colorchat reload or /cc reload: Reloads the plugin configuration (requires colorchat.admin permission)

Permissions

colorchat.use: Allows players to use color codes in chat messages
colorchat.admin: Allows access to administrative commands like reload

Configuration
The config.yml file contains settings for the plugin:
yaml# ColorChat Configuration

# General Settings
settings:
  # Enable/disable the plugin
  enabled: true
  
  # Character used for color codes (default: &)
  color-code-symbol: '&'
  
# Messages
messages:
  no-permission: '&cYou do not have permission to use color codes in chat.'
  plugin-enabled: '&aColorChat plugin has been enabled!'
  plugin-disabled: '&cColorChat plugin has been disabled!'
  config-reloaded: '&aConfiguration has been reloaded!'

# Permission Settings
permissions:
  # Should players with permission be able to use color codes
  use-color-codes: true
  
  # Should operators (OP players) have permission by default
  ops-have-permission: true
Support
If you encounter any issues with the plugin, please report them on the Discord!
License
This plugin is released under the MIT License.
