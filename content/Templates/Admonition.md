```ad-<% tp.system.suggester(["note", "seealso", "abstract", "summary", "tldr", "info", "todo", "tip", "hint", "important", "success", "check", "done", "question", "help", "faq", "warning", "caution", "attention", "failure", "fail", "missing", "danger", "error", "bug", "example", "quote", "cite"], ["note", "seealso", "abstract", "summary", "tldr", "info", "todo", "tip", "hint", "important", "success", "check", "done", "question", "help", "faq", "warning", "caution", "attention", "failure", "fail", "missing", "danger", "error", "bug", "example", "quote", "cite"]) %>
title: <% tp.system.prompt("What is the title?") %>
color: <% tp.system.suggester(["Red", "Green", "Blue", "Aqua", "Purple", "Orange", "Yellow", "Pink"], ["255, 0, 50", "150, 255, 50", "100, 100, 255", "150, 255, 255", "150, 50, 255", "255, 100, 0", "255, 200, 0", "255, 20, 100"]) %>

<% tp.file.cursor() %>
```