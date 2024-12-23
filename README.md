// Zed settings
//
// For information on how to configure Zed, see the Zed
// documentation: https://zed.dev/docs/configuring-zed
//
// To see all of Zed's default settings without changing your
// custom settings, run `zed: open default settings` from the
// command palette (cmd-shift-p / ctrl-shift-p)
{
  "assistant": {
    "default_model": {
      "provider": "zed.dev",
      "model": "claude-3-5-sonnet-latest"
    },
    "inline_alternatives": [{ "provider": "zed.dev", "model": "default" }],
    "version": "2",
    "enable_snippets": true,
    "dock": "left",
    "enable_completions": true,
    "max_results": 5,
    "max_results_per_model": 5,
    "enable_experimental_live_diffs": true
  },
  "auto_update": true,

  "telemetry": {
    "metrics": false
  },
  "features": {
    "inline_completion_provider": "supermaven"
  },
  "ui_font_size": 16,
  "buffer_font_size": 16,
  "inlay_hints": {
    "enabled": true,
    "show_type_hints": true
  },
  "theme": {
    "mode": "system",
    "light": "One Light",
    "dark": "Andromeda"
  },
  "buffer_font_family": "JetBrains Mono",
  "soft_wrap": "editor_width",
  "project_panel": {
    "dock": "right"
  },
  "autosave": "on_focus_change",
  "autosave_interval": 10,
  "terminal": {
    "cursor_shape": "bar",
    "font_family": "JetBrains Mono",
    "working_directory": "current_project_directory",
    "font_size": 13,
    "env": {
      "EDITOR": "zed --wait"
    }
  }
}
