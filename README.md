This project is controller program at Bve train sim.This controller is similar to the 113 series train controller. 基本構成（ここはしっかりと記録するため日本語で） ☆使用機器 Arduino UNO R4 ・加減速に関する入力 １.マスコン：可変抵抗10KΩ ２.ブレーキ：可変抵抗10KΩ

・走行に関するスイッチ １.定速：ボタン ２.逆転ハンドル：可変抵抗？（12/21模索中）

・保安機器類に関わるスイッチ 警笛類 １.警笛１:フットスイッチ ２.警笛２:フットスイッチ EB類 ３.EBリセットボタン：ボタン ATS類 ４.ATS確認ボタン：ボタン ５.警報持続：ボタン ６.ATSに切り替え：トグルスイッチ ７.ATCに切り替え：トグルスイッチ ８.復帰：引っ張るスイッチ ９.保安装置入り切り：トグルスイッチ

これらの状態を判断しPCへキーボードとして入力する
