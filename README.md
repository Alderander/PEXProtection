# PEXProtection
An addon plugin for the PureEntitiesX plugin.
Get the latest official release here: https://github.com/RevivalPMMP/PEXProtection/releases

## What is this plugin?
This plugin adds a way for Operators to change the way monsters are spawning automatically. Monsters can be blocked from spawning on certain places by adding a center and giving it a radius to block monster spawning within. This can be modified, removed and added using the centers.yml file.

## How does it work?
To start, you can use the command /pexprotection, or using the alias /pexp. To make a valid center protection block you need to follow this format when typing the command:     

    /pexprotection add <name> <radius>
    
After using this command, the plugin will tell you to select a block. You can select a block by tapping it, which will then be selected as the center block for the protection radius. When you've done that... You're done! Have fun!

## What are the permissions and commands?

    Commands:

    pexprotection:
        description: PEXProtection command
        usage: /pexprotection <add/del>
        aliases: [pexp]
        permission: pexprotection.command

    Permissions:      
    
    pexprotection.command:
        default: op
        description: Permission to use all PexProtection commands
