# ARKitDocuments
ARKit Documents in Korean

## About
  아래 문서의 요지를 정리함.
  
  *https://developer.apple.com/documentation/arkit*


## Overview
증강현실(AR)이란, 앞/뒤 카메라를 통해 보고있는 뷰에 2D 또는 3D 요소를 추가하는 사용자 경험이다.


## Augmented Reality with the Back Camera
가장 일반적인 AR 경험은 사용자 주위의 것들과 새로운 방식으로 상호작용할 수 있도록 iOS의 후면 카메라로 보는 뷰에 여러 시각적인 컨텐츠가 추가하여 보여주는것이다.
**ARWorldTrackingConfiguration**이 바로 이러한 경험을 제공한다. ARKit은 실세계 공간을 맵핑하고 트래킹하여 가상 컨텐츠를 좌표에 맞춰 배치한다. 뿐만 아니라 오브젝트나 이미지를 인식함으로써 사용자로 하여금 더욱 몰입할 수 있다.

>*Note:*
 >다음과 같은 방법으로 iOS 12는 3D 오브젝트를 추가한 AR뷰를 만들수 있다. 
 >- USDZ 파일 + **QLPreviewController**를 사용
 >- USDZ 파일 + Safari/WebKit 사용
 
  
## Augemented Reality with the Front Camera
아이폰X에선  **ARFaceTrackingConfiguration**을 통해 실세계 정보(포즈, 사용자 얼굴에 드러난 감정)를 가상 컨텐츠로 렌더링 할 수 있다.




[Jump to ARSession]()
