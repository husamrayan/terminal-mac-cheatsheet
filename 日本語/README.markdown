### ショートカット

| キー/コマンド | 説明 |
| ----------- | ----------- |
| Ctrl + A   | 現在入力している行の先頭に移動します。このコマンドは、ほとんどのテキスト入力でも動作します。Netbeansは例外です。 |
| Ctrl + E   | 現在入力している行の末尾に移動します。このコマンドは、ほとんどのテキスト入力でも動作します。Netbeansは例外です。 |
| Ctrl + L   | 画面をクリアする。 |
| Cmd + K    | 開始位置までクリアする。 |
| Ctrl + U   | 現在のカーソル位置から行頭までをカットする。 |
| Ctrl + K   | 現在のカーソル位置から行末までをカットする。 |
| Ctrl + W   | スペースを区切り文字として、現在のカーソル位置より前の単語をカットする。 |
| Ctrl + Y   | 最後のカットコマンドでカットしたものを貼り付ける。 |
| Ctrl + H   | バックスペースと同じ |
| Ctrl + C   | 現在のターミナルで実行中のどんなものも停止する。また、現在カーソルがある行をすべてクリアする。 |
| Ctrl + D   | 実行中のプロセスが存在しない場合に現在のシェルを終了するか、実行中のEOFを送信する。 |
| Ctrl + Z   | 実行中のプロセスを中断したバックグラウンドプロセスに挿入する。フォアグラウンドでこれを復元する。 |
| Ctrl + _   | 最後のコマンドを元に戻す。（アンダーバーを入力するため、USキーボードの場合はCtrl + Shift + マイナス(-)。) |
| Ctrl + T   | カーソル位置の前にある2つの文字を入れ替える。 |
| Ctrl + F   | カーソルを一文字右に移動する。 |
| Ctrl + B   | カーソルを一文字左に移動する。 |
| Option + →  | カーソルを一単語右に移動する。 |
| Option + ←  | カーソルを一単語左に移動する。 |
| Esc + T  | カーソル位置の前にある2つの単語を入れ替える。 |
| Tab  | ファイル名やフォルダ名を自動的に補完する。 |

### 重要なコマンド

| キー/コマンド | 説明 |
| ----------- | ----------- |
| cd [folder] | ディレクトリを変更する。 例) `cd Documents` |
| cd | ホームディレクトリに移動する。 |
| cd ~ | ホームディレクトリに移動する。 |
| cd /  | ドライブのルートに移動する。 |
| cd -  | 一つ上の階層のディレクトリに移動する |
| cd .. | 一つ上の階層のディレクトリに移動する |
| ls | 現在のディレクトリにあるファイルやディレクトリを表示する。 |
| ls -l | ファイルやディレクトリの詳細も同時に表示する。 |
| ls -a | 隠しファイルも含めすべてのファイルやディレクトリを表示する。 |
| ls -al | 隠しファイルも含めすべてのファイルやディレクトリの詳細を表示する。 |
| ls -lh| ファイルサイズの表記が含まれる詳細リスト |
| ls -R | 再帰的にすべてのフォルダの内容を表示する。 |
| sudo [command] | 管理者のセキュリティ権限でコマンドを実行する。（sudo = Super User DO） |
| open [file] | ファイルを開く。（ダブルクリックしたように） |
| top | 現在動作中のプロセスを表示する。qを押すと表示を終了する。 |
| nano [file] | nanoエディターを使用してファイルを開く。 |
| vim [file] | vimエディターを使用してファイルを開く。 |
| clear | 画面をクリアする。 |
| reset | ターミナル画面をリセットする。 |

### 連鎖コマンド

| キー/コマンド | 説明 |
| ----------- | ----------- |
| [command-a]; [command-b] | Aコマンドの成功にかかわらず、Aコマンドの実行後にBコマンドを実行する。 |
| [command-a] && [command-b] | Aコマンドが正常に実行されると、Bコマンドが実行される。 |
| [command-a] \|\| [command-b] | Aコマンドが失敗した場合、Bコマンドを実行する。 |
| [command-a] & | Aコマンドをバックグラウンドで実行する。 |


### パイプコマンド

| キー/コマンド | 説明 |
| ----------- | ----------- |
| [command-a] \| [command-b] | Aコマンドを実行し、その結果をBコマンドに渡す。 例) `ps auxwww \| grep google` |


### コマンド履歴

| キー/コマンド | 説明 |
| ----------- | ----------- |
| history n | 入力したものを表示する。nの部分に項目の数を指定する数字を入力する。 |
| Ctrl + r  | 以前に入力したコマンドをインタラクティブに検索する。 |
| ![value] | 「value」で始まる最後に入力されたコマンドを実行する。 |
| ![value]:p | 「value」で始まる最後に入力されたコマンドをコンソールに出力する。 |
| !! | 最後に入力したコマンドを実行する。 |
| !!:p | 最後に入力しtコマンドをコンソールに出力する。 |

### ファイル管理

| キー/コマンド | 説明 |
| ----------- | ----------- |
| touch [file] | 新規ファイルを作成する。 |
| pwd | 現在作業しているディレクトリのフルパスを表示する。 |
| . | 現在のフォルダ。 例) `ls .` |
| .. | 親/包含ディレクトリ。 例) `ls ..` |
| ls -l .. | 親ディレクトリの詳細も同時に表示する。 |
| cd ../../ | 二つ上の階層のディレクトリに移動する |
| cat | ファイルの内容をターミナルに表示する。 |
| rm [file] | ファイルを削除する。 例) `rm data.tmp` |
| rm -i [file] | ファイルを削除するときに、ユーザーに削除するかどうかを確認する。 |
| rm -r [dir] | ディレクトリとその中身を削除する。 |
| rm -f [file] | 確認なしに強制的にファイルを削除する。 |
| cp [file] [newfile] | ファイルを新しいファイルにコピーする。 |
| cp [file] [dir] | ファイルをディレクトリにコピーする。 |
| mv [file] [new filename] | ファイルを別のディレクトリに移動させる。/ファイル名を変更する。 例) `mv file1.ad /tmp` |
| pbcopy < [file] | ファイルの内容をクリップボードにコピーする。 |
| pbpaste | クリップボードの内容を貼り付ける。 |
| pbpaste > [file] | クリップボードの内容をファイルに貼り付ける。 例) `pbpaste > paste-test.txt` |

### ディレクトリ管理

| キー/コマンド | 説明 |
| ----------- | ----------- |
| mkdir [dir] | 新規ディレクトリを作成する。 |
| mkdir -p [dir]/[dir] | 階層化されたディレクトリを作成する。 |
| rmdir [dir] | ディレクトリを削除する。（空のディレクトリのみで動作する。） |
| rm -R [dir] | ディレクトリとその中身を削除する。 |
| less [file]| ファイルの内容をページ単位で表示する。 |
| [command] > [file] |  出力をファイルにプッシュする。上書きされることに注意する。 |
| [command] >> [file] | 出力を既存のファイルに追加する。 |
| [command] < [file] | ファイルの内容を読み取るように指示をする。 |

### 検索

| キー/コマンド | 説明 |
| ----------- | ----------- |
| find [dir] -name [search_pattern] | ファイルを検索する。 例) `find /Users -name "file.txt"` |
| grep [search_pattern] [file] | パターンを含むすべての行を検索する。 例) `grep "Tom" file.txt` |
| grep -r [search_pattern] [dir] | 指定されたディレクトリ内のすべてのファイルで、パターンを含むすべての行を再帰的に検索する。 |
| grep -v [search_pattern] [file] | パターンを含まないすべての行を検索する。 |
| grep -i [search_pattern] [file] | 大文字と小文字を区別しないパターンを含むすべての行を検索する。 |
| mdfind [search_pattern] | ファイルに対してSpotlight検索をする。（名前、内容、その他のメタデータ） 例) `mdfind skateboard` |
| mdfind -onlyin [dir] -name [pattern] | 指定されたディレクトリ内のパターンと類似した名前のファイルを検索する。 |

### ヘルプ

| キー/Command | 説明 |
| ----------- | ----------- |
| [command] -h | [command]のヘルプを表示する。 |
| [command] --help | [command]のヘルプを表示する。 |
| info [command] | [command]のヘルプを表示する。 |
| man [command] | [command]のヘルプマニュアルを表示する。 |
| whatis [command] | [command]の一行の説明を表示する。 |
| apropos [search-pattern] | 説明にキーワードを含むコマンドを検索する。 |