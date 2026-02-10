# 🔓 Open Sourcerer Achievement Guide

## Goal
Earn the **Open Sourcerer** achievement by having pull requests merged in 2+ public repositories.

---

## 🎯 3 Beginner-Friendly Issues Found

### 1. **Making emails clickable** (Easiest!)
- **Repository**: [Gooichand/blockchain-evidence](https://github.com/Gooichand/blockchain-evidence)
- **Issue**: [#223 - Making emails clickable](https://github.com/Gooichand/blockchain-evidence/issues/223)
- **Task**: Convert plain text email to clickable `mailto:` link in Privacy Policy
- **Difficulty**: ⭐ Very Easy (HTML change)
- **Estimated Time**: 5 minutes

**What to do:**
```html
<!-- Change from: -->
contact@example.com

<!-- To: -->
<a href="mailto:contact@example.com">contact@example.com</a>
```

---

### 2. **Build script for Windows** (Easy!)
- **Repository**: [pulpgrinder/GorillaPresenter](https://github.com/pulpgrinder/GorillaPresenter)
- **Issue**: [#19 - Need a build script for Windows systems](https://github.com/pulpgrinder/GorillaPresenter/issues/19)
- **Task**: Create a `.bat` file to run 3 Node.js programs in sequence
- **Difficulty**: ⭐⭐ Easy (Batch scripting)
- **Estimated Time**: 10 minutes

**What to do:**
Create a `build.bat` file with:
```batch
@echo off
node program1.js
node program2.js
node program3.js
```

---

### 3. **Increase color contrast** (Medium)
- **Repository**: [processing/p5.js-web-editor](https://github.com/processing/p5.js-web-editor)
- **Issue**: [#3856 - Increasing color contrast of Storage Bar](https://github.com/processing/p5.js-web-editor/issues/3856)
- **Task**: Fix WCAG contrast errors in the Assets Page
- **Difficulty**: ⭐⭐⭐ Medium (CSS + Accessibility)
- **Estimated Time**: 20 minutes

**What to do:**
Adjust CSS colors to meet WCAG contrast ratio requirements.

---

## 📝 Step-by-Step Contribution Process

### For Each Repository:

1. **Fork the repository**
   - Click "Fork" button on the repository page
   - This creates a copy in your account

2. **Clone your fork**
   ```bash
   git clone https://github.com/RaviShankar000/<repository-name>.git
   cd <repository-name>
   ```

3. **Create a new branch**
   ```bash
   git checkout -b fix-issue-<issue-number>
   ```

4. **Make the required changes**
   - Follow the issue description
   - Test your changes locally

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "Fix #<issue-number>: <brief description>"
   ```

6. **Push to your fork**
   ```bash
   git push origin fix-issue-<issue-number>
   ```

7. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your fork and branch
   - Reference the issue: "Fixes #<issue-number>"
   - Submit the PR

8. **Wait for review and merge**
   - Maintainers will review your PR
   - Make any requested changes
   - Once merged, you're one step closer to the achievement!

---

## ✅ Achievement Progress Tracker

- [ ] Fork Repository 1 (blockchain-evidence)
- [ ] Make changes for Issue #223
- [ ] Submit PR #1
- [ ] PR #1 Merged ✅

- [ ] Fork Repository 2 (GorillaPresenter)
- [ ] Make changes for Issue #19
- [ ] Submit PR #2
- [ ] PR #2 Merged ✅

- [ ] Fork Repository 3 (p5.js-web-editor)
- [ ] Make changes for Issue #3856
- [ ] Submit PR #3
- [ ] PR #3 Merged ✅

**Once 2+ PRs are merged, you'll earn the Open Sourcerer achievement! 🎉**

---

## 💡 Tips for Success

1. **Read the contribution guidelines** (usually in `CONTRIBUTING.md`)
2. **Be polite and professional** in all communications
3. **Test your changes** before submitting
4. **Reference the issue number** in your PR description
5. **Be patient** - reviews can take time
6. **Ask questions** if you're unsure about anything

Good luck! 🚀
