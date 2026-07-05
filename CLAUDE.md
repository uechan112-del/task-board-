# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

`task-board` は新規プロジェクト（初期セットアップ段階）。具体的な仕様・技術構成は今後の開発に応じて追記する。

## Git運用ルール

- **コードに変更を加えたら、その都度コミットしてGitHubにプッシュすること。** 変更をローカルに溜め込まず、1つの作業（機能追加・修正など）が完了するたびに commit → push まで行う。
- コミットメッセージは変更内容が分かるように具体的に書く。
- force push（`git push --force` 等）や履歴の書き換えは行わない。
- push前に `git status` / `git diff` で変更内容を確認し、意図しないファイルを含めない。

## GitHubリポジトリ
https://github.com/uechan112-del/task-board-.git

## 制約・注意点

- 本プロジェクトは `Claude_Work` フォルダ配下のサブプロジェクトであり、フォルダ全体の運用ルール（削除・上書き前の確認、日付形式など）は親フォルダの `CLAUDE.md` に従うこと。
