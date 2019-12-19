# RNN-Music-Composition
This project use the Recurrent Neural Network (RNN) with Bi-Directional Gate Recurrent Units (GRU) and Self- Attention layers to learn music composition
このシステムはリカレントニューラネットワーク（RNN）にGRUユニイトと『SelfーAttention僧』を用いた自動作曲です。

## 説明文
1. 『Tensorflow 2.0』,『Numpy』,『Music21』、『Pretty＿midi』をローカルにパイトンでインストールすることが必要になります。
2. 入力データとしてはチョパン曲のMidiファイルを使って、Pretty_midiでピアノロールのようにタイムステップと音符のデータに変換させる。
3. そして、全ての曲は『Cmaj』キーと『Aminor』　キーに変換させます。（学習を安くさせるため）
4. ご注意のは１のエポックが１時間ぐらいかかります。（GPU:Radeon Pro 460）
5.　学習した後、二つの関数で『generate_from_random』と『generate_from_one_note』を二つのMidiファイルを学習した曲のパタンで曲を発生させます。
