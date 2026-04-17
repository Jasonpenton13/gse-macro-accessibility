# gse-macro-accessibility
Accessibility-focused macro system for World of Warcraft using GSE to assist players with limited mobility

# GSE Macro Accessibility Project

## Overview
This project focuses on creating automation macros using the GSE addon in World of Warcraft to improve accessibility for players with limited mobility.

## Features
- Reduces number of required key presses
- Automates ability sequences
- Improves reaction timing requirements
- Custom macro logic for better usability

## Technical Details
- Built using GSE (Gnome Sequencer Enhanced)
- Macro logic structured into modular sequences
- Handles conditional ability execution and priority systems

## Challenges Solved
- Fixed issues with abilities not triggering (e.g., Judgment, Divine Toll)
- Improved macro reliability in live combat scenarios
- Adjusted sequences for compatibility with new GSE system

## Future Improvements
- Expand support for more classes/specs
- Add user customization options
- Further optimize performance

## Author
Jason Penton

{
    [1] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Avenger's Shield
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Avenger's Shield
]],
        ["type"] = "macro",
        ["blockPath"] = "1"
    },
    [2] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [known:Hammer of Light,nochanneling] Hammer of Light; [nochanneling] Shield of the Righteous
/cast [combat,nochanneling] Avenging Wrath
]],
        ["type"] = "macro",
        ["blockPath"] = "2"
    },
    [3] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/castsequence [mod:ctrl,nochanneling] Word of Glory; [nochanneling]   reset=combat  Blessed Hammer, Consecration, Blessed Hammer, Blessed Hammer
]],
        ["type"] = "macro",
        ["blockPath"] = "3"
    },
    [4] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:alt,nochanneling] Word of Glory; [combat,nochanneling] Divine Toll
]],
        ["type"] = "macro",
        ["blockPath"] = "4"
    },
    [5] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
]],
        ["type"] = "macro",
        ["blockPath"] = "5"
    },
    [6] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Avenger's Shield
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Avenger's Shield
]],
        ["type"] = "macro",
        ["blockPath"] = "6.1"
    },
    [7] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/castsequence [mod:ctrl,nochanneling] Word of Glory; [nochanneling]   reset=combat  Blessed Hammer, Consecration, Blessed Hammer, Blessed Hammer
]],
        ["type"] = "macro",
        ["blockPath"] = "3"
    },
    [8] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
]],
        ["type"] = "macro",
        ["blockPath"] = "5"
    },
    [9] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [known:Hammer of Light,nochanneling] Hammer of Light; [nochanneling] Shield of the Righteous
/cast [combat,nochanneling] Avenging Wrath
]],
        ["type"] = "macro",
        ["blockPath"] = "2"
    },
    [10] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:alt,nochanneling] Word of Glory; [combat,nochanneling] Divine Toll
]],
        ["type"] = "macro",
        ["blockPath"] = "4"
    },
    [11] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
]],
        ["type"] = "macro",
        ["blockPath"] = "5"
    },
    [12] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/castsequence [mod:ctrl,nochanneling] Word of Glory; [nochanneling]   reset=combat  Blessed Hammer, Consecration, Blessed Hammer, Blessed Hammer
]],
        ["type"] = "macro",
        ["blockPath"] = "3"
    },
    [13] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Avenger's Shield
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Avenger's Shield
]],
        ["type"] = "macro",
        ["blockPath"] = "1"
    },
    [14] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
]],
        ["type"] = "macro",
        ["blockPath"] = "5"
    },
    [15] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/castsequence [mod:ctrl,nochanneling] Word of Glory; [nochanneling]   reset=combat  Blessed Hammer, Consecration, Blessed Hammer, Blessed Hammer
]],
        ["type"] = "macro",
        ["blockPath"] = "3"
    },
    [16] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:alt,nochanneling] Word of Glory; [combat,nochanneling] Divine Toll
]],
        ["type"] = "macro",
        ["blockPath"] = "4"
    },
    [17] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
]],
        ["type"] = "macro",
        ["blockPath"] = "5"
    },
    [18] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [known:Hammer of Light,nochanneling] Hammer of Light; [nochanneling] Shield of the Righteous
/cast [combat,nochanneling] Avenging Wrath
]],
        ["type"] = "macro",
        ["blockPath"] = "2"
    },
    [19] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/castsequence [mod:ctrl,nochanneling] Word of Glory; [nochanneling]   reset=combat  Blessed Hammer, Consecration, Blessed Hammer, Blessed Hammer
]],
        ["type"] = "macro",
        ["blockPath"] = "3"
    },
    [20] = {
        ["macrotext"] = [[
/targetenemy [noharm][dead]
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
/cast [mod:ctrl,nochanneling] Word of Glory; [nochanneling] Judgment
]],
