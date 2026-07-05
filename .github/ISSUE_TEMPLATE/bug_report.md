---
name: Bug Report
about: Report a bug or unexpected behavior in flyline.
title: "[BUG] "
labels: bug
assignees: ''
---

> [!IMPORTANT]
> Please make sure you are on the latest version of flyline!

### Describe the Bug
A clear and concise description of what the bug is and what you expected to happen.

---

### Environment & Version Information
Please run the following command in your terminal and paste the copied contents in the box below:
```bash
flyline version --copy
```

*Paste results here:*
```text
<paste here>
```

---

### Debug Logs (Optional / If Necessary)
If logs are necessary to help diagnose the issue (e.g., terminal crashes, keybinding conflicts, or suggestions failing):

1. Enable debug logging:
   ```bash
   flyline log set-level debug
   ```
2. Recreate the issue in your terminal.
3. Copy the last 10 seconds of logs to your clipboard:
   ```bash
   flyline log copy --last 10s
   ```
4. Paste the logs inside the expandable block below:

*Paste logs here:*
<details>
<summary>Click to expand logs</summary>

```text
<paste here>
```

</details>

---

### Steps to Reproduce
Steps to reproduce the behavior:
1. Go to '...'
2. Press keys '...'
3. See error '...'
