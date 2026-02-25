# shared dotfiles

stow는 GNU Stow라는 도구로, 여러 디렉토리에 걸쳐 있는 파일들을 관리하기 쉽게 해주는 소프트웨어입니다. 이 도구를 사용하면, 예를 들어 `opencode`와 `tmux`와 같은 디렉토리에 있는 설정 파일들을 홈 디렉토리에 심볼릭 링크로 연결하여 관리할 수 있습니다.

```bash
brew install stow

stow opencode
stow tmux
```
