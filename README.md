# Puluse_graph_analysis  

##1.説明  
- 右手の親指をノートPCのカメラで撮影し、フレームごとに画像を取得し、平均輝度値を分析する。その輝度値の変化をグラフにプロットして脈の変化を観測する。  

##2.手順  
- cv2をimportする。動画ファイルを読み込み、スクリーンキャプチャを保存するディレクトリを作成。フレームごとに番号を振って保存。  
- それぞれの画像の平均輝度値をベクトルに代入し、プロットした。  

##3.結果  
- 60fpsの条件で78枚の写真を用いたため、1.3[sec]分撮影したと言える。  
- 波形を見ると約5.5周期であったため、脈拍は253bpmとなった。また、2周期ごとに一回脈を売っっていると仮定すると、127bpmであった。  
- 人間の脈拍より異常に数値が高くなっているが、撮影した際に緊張していた可能性が考えられる。  

##4.参考  
- 動画をフレームごとにスクリーンキャプチャとして保存する方法は次のページを参考にした。<https://www.tech-tech.xyz/opencv_video.html>
