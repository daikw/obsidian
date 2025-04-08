
# Cline

とりあえずソースコードを読む
https://github.com/cline/cline
- changesets/cli が利用されている
	- https://github.com/cline/cline/blob/main/.changeset/README.md
- システムプロンプト
	- https://github.com/cline/cline/blob/main/src/core/prompts/system.ts
	- とても長い、全部入りっぽい
	- 有効な MCP がツールとして使えると指示
	- browserSetting がコンテキストに入っている、その情報まで考えさせるのは筋悪じゃないか？

# Roo Code
とりあえずソースコードを読む

- システムプロンプト
	- https://github.com/RooVetGit/Roo-Code/blob/main/src/core/prompts/tools/index.ts
	- システムプロンプトに記載するツールを、起動モードによって動的に変更している
	- 
