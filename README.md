# opencv1
cv2.VideoCapture() で VideoCapture オブジェクトを取得します.  
カメラから連続的に画像を取得するため、ここでは while 文で繰り返し処理を行います。
while 内の最初で、カメラから1コマのデータを取得するため capture.read() を呼び出しています。 
取得した1コマの画像データは、変数 frame に代入されています。  
OpenCVのcv2.imshow()メソッドでOSのフレームに画像を表示します。  
while内でループを止めるために[q]キーがタイプされたらberakするif文を記述しています。  
while を抜けると、処理を終了させるために VideoCapture を終了して、開いたウィンドウも終了させます。
