# todo.hs-addons
Addons for todo.hs

See [jecxjo/todo.hs](https://github.com/jecxjo/todo.hs) for my todo.txt app.

## List of Addons

### Github

Using the customizable tag `gh` and a customizable domain, you can store your
Github urls into your tasks and launch a brower directly to them.

```
$ todo
1: (A) Fix @bug in +todohs gh:jecxjo/todo.hs
2: (B) Review PR gh:jecxjo/todo.hs/pull/1234

$ todo github 2
Opening https://github.com/jecxjo/todo.hs/pull/1234
```

Or change the tag and domain to anything else you'd like to link to such as
Jira.

