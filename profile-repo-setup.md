# GitHub Profile Repository Setup

GitHub 프로필 README를 적용하려면 username과 같은 이름의 public repository가 필요하다.

- GitHub user: `scnelMG`
- Profile repository: `scnelMG/scnelMG`
- Main file: `README.md`

## 적용 명령

외부 GitHub 리소스를 생성/수정하므로 사용자 승인 후 실행한다.

```bash
cd work/github-profile
git init
git add README.md profile-repo-setup.md
git commit -m "docs: add GitHub profile README"
gh repo create scnelMG --public --source=. --remote=origin --push
```

이미 `scnelMG/scnelMG` repository를 웹에서 생성한 경우:

```bash
cd work/github-profile
git init
git add README.md profile-repo-setup.md
git commit -m "docs: add GitHub profile README"
git remote add origin https://github.com/scnelMG/scnelMG.git
git push -u origin main
```
