# How to make your first contribution

You can complete this challenge after the workshop. You need a free GitHub account.

## Option A — Using Git on your computer

1. Click **Fork** on the original repository to create your own copy.
2. On your fork, click **Code → HTTPS** and copy the URL.
3. In a terminal, run:

```bash
git clone https://github.com/YOUR-USERNAME/binary-beginning-first-contribution.git
cd binary-beginning-first-contribution
git switch -c add-yourname
```

4. Create a file named `contributors/YOUR-USERNAME.md` (replace the placeholder with your GitHub username). Follow [contributors/example.md](contributors/example.md).
5. Stage and commit:

```bash
git add contributors/
git commit -m "Add my introduction"
git push -u origin add-yourname
```

6. Open your fork on GitHub. Click **Compare & pull request** (or **Contribute → Open pull request**).
7. Verify that the **base repository** is `Kaustav-coder-hub/binary-beginning-first-contribution`, **base branch** is `main`, and the **head** is your fork's `add-yourname` branch.
8. Write a short PR title such as `Add YOUR-USERNAME introduction` and click **Create pull request**.

## Option B — Using GitHub in your browser

1. Fork the repository.
2. In your fork, use the branch selector to create a branch named `add-yourname`.
3. Click **Add file → Create new file** and enter `contributors/YOUR-USERNAME.md`.
4. Add your introduction following the example, then commit to your new branch.
5. Use **Contribute → Open pull request** and confirm the base repository and branch before submitting.

## Rules
- One introduction file per participant.
- Use your GitHub username as the filename to avoid collisions.
- Keep content respectful and appropriate for a public repository.
- Never post phone numbers, email addresses, student IDs, passwords, or other private details.
- Do not modify other participants' files.
- Opening a PR completes the challenge; merging depends on review.

If Git asks you to configure your identity, run `git config --global user.name "Your Name"` and `git config --global user.email "your-github-commit-email"`. Use a GitHub-provided no-reply email if you prefer privacy.
