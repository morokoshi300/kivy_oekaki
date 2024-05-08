#  データサイエンスプロジェクトⅲ,ⅳの制作物

main.pyがkivymdで作り直した新メインファイル  
main.kvが新レイアウト用のKv language  
kivy1.pyが旧メインファイル  
kivy2.pyが画像のメタデータ確認用  
kivy3.pyがなんかいろいろするとこ  
paint.kvが旧レイアウト用のKv language  

### todo

- [x] - 塗り絵部分のUI作成
- [x] - 塗りつぶしの実装
- [ ] ↳ 塗りつぶしの精度改善
- [ ] - ギャラリーの実装
- [ ] ↳ ギャラリーの画像に埋め込まれたメタデータからcanvasを復元
- [ ] - 塗り絵の元絵自動生成部分の実装
- [ ] ↳ opencvを用い写真から線画を抽出
- [ ] ↳ Diffusersを用い元絵を生成する
- [ ] ↳ Diffusersを用い線画を抽出
- [ ] ↳ 教員が線画画像から塗り絵を作成する部分の実装
- [ ] - 塗り絵選択UIの実装
- [x] - kivymdでのUIリメイク（基幹部分の移し替え80%）

### 進捗+緊急todo
kivy1.pyの内容をkivymdで構築しなおしmain.pyに移す作業が80%完了  
細かな保存などはまだ移し終わってない  
仮実装で塗り絵の元絵読み込み機能実装  
元絵をアス比を変更せずにリスケールしてから配置する機能を実装する  
- [ ] - 元絵をアス比を変更せずにリスケールしてから配置する機能を実装する  
