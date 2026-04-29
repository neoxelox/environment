# Themes

- macOS Classic Theme
- Colored Zed Icons Theme

# Extensions

- HTML
- TOML
- SQL
- XML
- Biome
- Git Firefly
- Dockerfile
- SCSS & SASS
- Swift
- Emmet
- Zig
- Basher
- golangci-lint

# Configuration

```json
// Zed settings
//
// For information on how to configure Zed, see the Zed
// documentation: https://zed.dev/docs/configuring-zed
//
// To see all of Zed's default settings without changing your
// custom settings, run `zed: open default settings` from the
// command palette (cmd-shift-p / ctrl-shift-p)
{
  "collaboration_panel": {
    "button": false
  },
  "git_panel": {
    "show_count_badge": true,
    "file_icons": true,
    "status_style": "label_color"
  },
  "outline_panel": {
    "button": false
  },
  "terminal": {
    "show_count_badge": true
  },
  "tabs": {
    "show_diagnostics": "all",
    "file_icons": true,
    "git_status": true
  },
  "tab_bar": {
    "show": true
  },
  "title_bar": {
    "show_menus": false,
    "show_user_picture": false,
    "show_sign_in": false,
    "show_branch_status_icon": false
  },
  "status_bar": {
    "show_active_file": true
  },
  "project_panel": {
    "hide_root": true,
    "git_status_indicator": true,
    "diagnostic_badges": false,
    "auto_fold_dirs": false,
    "button": true
  },
  "search": {
    "button": true,
    "center_on_match": true
  },
  "toolbar": {
    "breadcrumbs": false,
    "quick_actions": false,
    "selections_menu": true,
    "agent_review": true,
    "code_actions": false
  },
  "multi_cursor_modifier": "alt",
  "git": {
    "inline_blame": {
      "enabled": false
    }
  },
  "icon_theme": {
    "mode": "system",
    "light": "Colored Zed Icons Theme Light",
    "dark": "Colored Zed Icons Theme Dark"
  },
  "languages": {
    "TypeScript": {
      "inlay_hints": {
        "enabled": false
      },
      "show_completion_documentation": true
    }
  },
  "agent": {
    "notify_when_agent_waiting": "all_screens",
    "single_file_review": true,
    "use_modifier_to_send": true,
    "play_sound_when_agent_done": "always",
    "favorite_models": [],
    "model_parameters": [],
    "show_turn_stats": true
  },
  "proxy": "",
  "inlay_hints": {
    "enabled": false
  },
  "cli_default_open_behavior": "new_window",
  "on_last_window_closed": "quit_app",
  "diff_view_style": "unified",
  "telemetry": {
    "diagnostics": false,
    "metrics": false
  },
  "session": {
    "trust_all_worktrees": true
  },
  "preview_tabs": {
    "enabled": false
  },
  "minimap": {
    "show": "never"
  },
  "cursor_blink": true,
  "buffer_font_fallbacks": [
    "Monaco",
    "Courier New",
    "monospace"
  ],
  "buffer_font_family": "Menlo",
  "file_types": {
    "dotenv": [
      ".env*"
    ]
  },
  "colorize_brackets": true,
  "show_edit_predictions": false,
  "indent_guides": {
    "background_coloring": "disabled",
    "active_line_width": 2,
    "line_width": 1,
    "coloring": "indent_aware",
    "enabled": true
  },
  "agent_servers": {
    "claude-acp": {
      "default_config_options": {
        "effort": "xhigh",
        "model": "opus[1m]",
        "mode": "acceptEdits"
      },
      "type": "registry"
    }
  },
  "base_keymap": "VSCode",
  "ui_font_size": 16,
  "buffer_font_size": 14.0,
  "theme": {
    "mode": "system",
    "light": "macOS Classic Light",
    "dark": "macOS Classic Dark",
  },
}
```

# Keymap

```json
// Zed keymap
//
// For information on binding keys, see the Zed
// documentation: https://zed.dev/docs/key-bindings
//
// To see the default key bindings run `zed: open default keymap`
// from the command palette.
[
  {
    "context": "Workspace",
    "bindings": {
      // "shift shift": "file_finder::Toggle"
    },
  },
  {
    "context": "Editor && vim_mode == insert",
    "bindings": {
      // "j k": "vim::NormalBefore"
    },
  },
  {
    "context": "ProjectSearchBar",
    "bindings": {
      "alt-f": "search::FocusSearch"
    }
  },
  {
    "context": "ProjectSearchBar",
    "unbind": {
      "cmd-shift-f": "search::FocusSearch"
    }
  },
  {
    "context": "Pane",
    "bindings": {
      "alt-f": "pane::DeploySearch"
    }
  },
  {
    "context": "Pane",
    "unbind": {
      "cmd-shift-f": "pane::DeploySearch"
    }
  },
  {
    "context": "Workspace",
    "bindings": {
      "alt-f": "pane::DeploySearch"
    }
  },
  {
    "context": "Workspace",
    "unbind": {
      "cmd-shift-f": "pane::DeploySearch"
    }
  },
  {
    "context": "Terminal",
    "bindings": {
      "ctrl-cmd-f": [
        "terminal::SendText",
        "\u001bf"
      ]
    }
  },
  {
    "context": "Terminal",
    "unbind": {
      "alt-f": [
        "terminal::SendText",
        "\u001bf"
      ]
    }
  },
  {
    "bindings": {
      "ctrl-alt-cmd-s": "zed::ToggleFullScreen"
    }
  },
  {
    "unbind": {
      "ctrl-cmd-f": "zed::ToggleFullScreen"
    }
  },
  {
    "context": "Workspace",
    "bindings": {
      "alt-s": "workspace::SaveWithoutFormat"
    }
  },
  {
    "context": "Workspace",
    "unbind": {
      "cmd-k s": "workspace::SaveWithoutFormat"
    }
  }
]
```
