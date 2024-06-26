## Holl_In_Wall

# プロジェクト README

## 内容
このプロジェクトは、Kinectを用いて指定の動作により、穴の開いた壁が鑑賞者にぶつかって跳ね返る、またはぶつからずにすり抜けるといった動的な変化を仮想的に実現することで、壁をすり抜ける感覚を表現したインタラクティブコンテンツです。

## このプロジェクトが解決する課題
このプロジェクトの目的は、映像に対して、身体を利用したインタラクション性を持たせることによって、目の前の映像があたかも現実空間の一部であるかのように感じる臨場感を実現することです。

## 学んだこと
このプロジェクトを通じて、TouchDesignerとPython、Kincetのセンサー技術について学びました。

## 操作方法
1. まず、Holl_In_Wall.toeを開きます(TOPViewer左画面または最上位階層のOP('Test')が位置調整画面、TOPViewer右画面または最上位階層のOP('display')がプレイヤー画面になります)。
2. 次にお使いのPCとKinectを接続してください(本データTestはKinect v1での接続設定となっているため、OP('project1')の階層に入り、OP('kinect2')のHardware Versionパラメータで任意のバージョンに変更してください)。
3. タイトル画面が表示されるので、Kinectを地面に置いて10°程度上に傾け、Kinectから3m程度離れた位置に立って認識させてください。認識させるとTest monitorと表示されている画面(OP('Test')の画面)に白いSphereオブジェクトが複数表示されます。
4. 白いSphereオブジェクトが身体の各部位の動きと連動するか確認し、静止している白いSphereオブジェクトを基準にして、Kinectの角度や位置の調整を行ってください。
5. OP('display')の画面にHold left hand to playと表示されているときに、両手を前に出して左手を一回握ると穴の開いた壁が奥から手前に向かってきます。その穴に通り抜けられる位置にKinectと連動させたSphereオブジェクトが全て入っていると、壁をすり抜けることが出来ます。
6. Kinectと連動させたSphereオブジェクトが壁に１つでも衝突すると壁が反射します。
7. 両手を前に出して右手を一回握ると壁の種類を変更することが出来ます(15秒間のインターバルあり)。

