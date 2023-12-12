# Info
This file is for uncategorized todos, as a quick idea sketchpad.

After adding them in here, there should be a place to categorize them.
This should live in a well-known Ctrl+# hotkey, in a well-known session.


# todos
- create an action (tmux) for going back to previous session 
- should have a session that's just for ideas, a session for development, etc
    - session for ideas should have a window structure that doesn't change
### research
- find tools for customization backend
    - kind of like i18n, should get the user's options as needed

# todos
- should have a script that reorganizes the todos in a file (this one) according 
    - can use that tool (tasker) that adds tasks    
        - add another tool that adds it to a todo file
        - can call the backend server that i have set up with a dsl prefix, by selecting a whole line
        - e.g. `atr this is my todo` means `add-todo-research`
            - which will create this todo in the current file, in the right category, and move the cursor next to it
    - should be able to send a todo from one file to current task queue, and back
        - it should automatically have the correct tags and fall in the right section
- figure out tools for documentation, documentation generation
    - best practices
- token/tag/category services
    - ensure that every token/tag/category created is unique
    - each should have metadata, giving info about what it means and what it's used for
    - can look up these tags, look up their usages, and filter by project type/other criteria
        - after creating infra for higher-level operations, should be able to functionally program codegen (e.g. map an action to multiple categories/tags of dsl/modules)
    - can also have feature service, that tags certain cross-cutting features
## vim hotkeys
- global navigator
    - searches through everything globally, and if something is open in a tmux pane/window/session somewhere, switch to it 
    - otherwise, provide actions i can take on found files/tasks
        - list it by category (project, tag, category, code, documentation)
# todos
## learning
- terminial development 
    - https://xn--rpa.cc/irl/term.html
    - https://viewsourcecode.org/snaptoken/kilo/02.enteringRawMode.html
    - https://en.wikipedia.org/wiki/ANSI_escape_code#Colors
