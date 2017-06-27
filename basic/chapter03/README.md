# THREE JS 광원

## THREE.AmbientLight
기본 광원을 가진 Scene안의 객체의 색상에 빛의 색상이 추가된다.

## THREE.PointLight
한 점에서 모든 방향으로 확산되는 빛, 그러나 그림자를 만들 수는 없다.

## THREE.SpotLight
램프나 천장의 등, 횃불 같은 원뿔 효과를 가진다, 이건 그림자를 만들 수 있다.

## THREE.DirectionalLight
무한광이라 부르는데 이광원의 광선은 태양광과 비슷하다, 이것은 그림자를 만들 수 있다.

## THREE.HemisphereLight
표면 반사나 희미한 하늘을 흉내내어 좀 더 자연스런 외부광을 만든느데 사용한다, 그림자를 못만든다.

## THREE.AreaLight
공간에서 한 지점 대신 빛을 발산하는 공간을 지정할 수 있다. 그림자 못만든다.

## THREE.LensFlare
광원은 아니지만 Scene에 렌즈 플레어 효과를 줄수 있다.

## 정리
AmbientLight, PointLight, SpotLight, DirectionalLight는 THREE.Light객체를 확장한것으로 공통된 기능을 제공한다.

나머지 3개의 광원은 특별한 목적이 있다. 그렇기에 위에 4개의 광원을 살핀후 나머지 3개의 광원을 살피도록 한다.

# THREE COLOR 속성

## set(value)

## setHex(value)

## setRGB(r,g,b)

## setHSL(h,s,l)

