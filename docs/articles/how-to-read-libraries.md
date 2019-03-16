description: C++ の標準ライブラリの読みと名前の由来の紹介

# 標準ライブラリの読みと名前の由来

## C++ の標準ライブラリ

| ライブラリ名             | 読み                           | 名前の由来                           |
|--------------------|------------------------------|---------------------------------|
| algorithm          | アルゴリズム                       | アルゴリズム                          |
| any                | エニー                          | なんでも                            |
| array              | アレイ                          | 配列                              |
| atomic             | アトミック                        | 不可分性                            |
| bit                | ビット                          | ビット演算                           |
| bitset             | ビットセット                       | ビット集合                           |
| charconv           | チャーコンブ/キャラコンブ                | 文字の変換 (character conversion) の略 |
| chrono             | クロノ                          | 時間 (ギリシャ語の Chronus に由来)         |
| codecvt            | コードコンバート/コードシーブイティー          | 文字コード変換                         |
| compare            | コンペア                         | 比較                              |
| complex            | コンプレックス                      | 複素数                             |
| concepts           | コンセプト                        | コンセプト                           |
| condition_variable | コンディション・ヴァリアブル               | 条件変数                            |
| contract           | コントラクト                       | 契約                              |
| coroutine          | コルーチン                        | コルーチン                           |
| deque              | デック/デキュー                     | 両端キュー (double ended queue) の略   |
| exception          | エクセプション                      | 例外                              |
| execution          | エグゼキューション                    | 実行                              |
| filesystem         | ファイルシステム                     | ファイルシステム                        |
| forward_list       | フォワード・リスト                    | 単方向リスト                          |
| fstream            | エフストリーム                      | ファイル用ストリーム                      |
| functional         | ファンクショナル                     | 関数の                             |
| future             | フューチャー                       | 未来                              |
| initializer_list   | イニシャライザー・リスト                 | 初期化リスト                          |
| iomanip            | アイオーマニピュ                     | 入出力の操作 (manipulator)            |
| ios                | アイオーエス                       | 入出力ストリーム                        |
| iosfwd             | アイオーエスフォワード                  | 入出力ストリームの前方宣言                   |
| iostream           | アイオーストリーム                    | 標準入出力ストリーム                      |
| istream            | アイストリーム                      | 入力ストリーム                         |
| iterator           | イテレーター                       | 反復子                             |
| limits             | リミッツ                         | 上限下限                            |
| list               | リスト                          | リスト                             |
| locale             | ロケール                         | 地域                              |
| map                | マップ                          | マップ                             |
| memory             | メモリー                         | メモリー                            |
| memory_resource    | メモリー・リソース                    | メモリーリソース                        |
| mutex              | ミューテックス                      | 排他制御 (mutual exclusion) の略      |
| new                | ニュー                          | 新しい                             |
| numeric            | ニューメリック                      | 数値的な                            |
| optional           | オプショナル                       | 選択できる                           |
| ostream            | オーストリーム                      | 出力ストリーム                         |
| queue              | キュー                          | キュー                             |
| random             | ランダム                         | 乱数                              |
| ranges             | レンジ                          | 範囲                              |
| ratio              | レシオ                          | 有理数                             |
| regex              | レジェックス                       | 正規表現 (regular expression) の略    |
| scoped_allocator   | スコープド・アロケーター                 | 範囲を決めたアロケータ                     |
| set                | セット                          | 集合                              |
| shared_mutex       | シェアード・ミューテックス                | 共有的な mutex                      |
| span               | スパン                          | 範囲                              |
| sstream            | エスストリーム                      | 文字列のストリーム                       |
| stack              | スタック                         | スタック                            |
| stdexcept          | エスティーディーエクセプト/スタンダードアーグエクセプト | 標準的な例外                          |
| streambuf          | ストリームバフ/ストームバッファー            | ストリームバッファー                      |
| string             | ストリング                        | 文字列                             |
| string_view        | ストリングビュー                     | 文字列のビュー                         |
| strstream          | エスティーアールストリーム/ストラストリーム       | 文字列のストリーム                       |
| syncstream         | シンクストリーム                     | 同期的なストリーム                       |
| system_error       | システム・エラー                     | システムエラー                         |
| thread             | スレッド                         | スレッド                            |
| tuple              | タプル                          | 値の組                             |
| typeindex          | タイプインデックス                    | タイプインデックス                       |
| typeinfo           | タイプインフォ                      | 型の情報                            |
| type_traits        | タイプ・トレイツ                     | 型の特徴                            |
| unordered_map      | アンオーダード・マップ                  | 非順序な map                        |
| unordered_set      | アンオーダード・セット                  | 非順序な set                        |
| utility            | ユーティリティー                     | 便利機能                            |
| valarray           | ヴァルアレイ                       | 値の配列                            |
| variant            | ヴァリアント                       | 相違した                            |
| vector             | ベクター                         | ベクトル                            |
| version            | バージョン                        | バージョン                           |

## C 言語由来の標準ライブラリ

| ライブラリ名    | 読み                          | 名前の由来                              |
|-----------|-----------------------------|------------------------------------|
| cassert   | シーアサート                      | 表明                                 |
| cctype    | シーシータイプ                     | 文字の分類                              |
| cerrno    | シーエラーナンバー                   | エラーナンバー (error number) の略          |
| cfenv     | シーエフエンブ                     | 浮動小数点数の環境設定 (float environment) の略 |
| cfloat    | シーフロート                      | 浮動小数点数                             |
| cinttypes | シーイントタイプス                   | 整数型                                |
| climits   | シーリミッツ                      | 上限下限                               |
| clocale   | シーロケール                      | 地域                                 |
| cmath     | シーマス                        | 数学関数                               |
| csetjmp   | シーセットジャンプ                   | セットジャンプ命令                          |
| csignal   | シーシグナル                      | シグナル                               |
| cstdarg   | シーエスティーディーアーグ/シースタンダードアーグ   | 引数                                 |
| cstddef   | シーエスティーディーデフ/シースタンダードデフ     | 基本的な定義                             |
| cstdint   | シーエスティーディーイント/シースタンダードイント   | 基本的な整数                             |
| cstdio    | シーエスティーディーアイオー/シースタンダードアイオー | 基本的な入出力                            |
| cstdlib   | シーエスティーディーリブ/シースタンダードリブ     | 基本的なライブラリ                          |
| cstring   | シーストリング                     | 文字列                                |
| ctime     | シータイム                       | 時間                                 |
| cuchar    | シーユーチャー                     | Unicode 文字                         |
| cwchar    | シーダブルチャー                    | ワイド文字                              |
| cwctype   | シーダブルタイプ                    | ワイド文字の分類                           |