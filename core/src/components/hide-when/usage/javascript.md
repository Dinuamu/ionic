```html
<ion-content padding>

  <h2>Mode Tests</h2>
  <ion-hide-when modes="md, ios">
    <div>Hides on MD, iOS</div>
  </ion-hide-when>

  <ion-hide-when modes="md">
    <div>Hides on MD only</div>
  </ion-hide-when>

  <ion-hide-when modes="ios">
    <div>Hides on iOS only</div>
  </ion-hide-when>

  <h2>Orientation Tests</h2>
  <ion-hide-when orientation="portrait">
    <div>Hides on portrait orientation</div>
  </ion-hide-when>

  <ion-hide-when orientation="landscape">
    <div>Hides on landscape orientation</div>
  </ion-hide-when>

  <h2>Platform Tests</h2>

  <ion-hide-when platform="android,ios">
    <div>Hides on Android and iOS</div>
  </ion-hide-when>

  <ion-hide-when platform="ios">
    <div>Only hide on iOS</div>
  </ion-hide-when>

  <ion-hide-when platform="android">
    <div>Only hide on Android</div>
  </ion-hide-when>

  <ion-hide-when platform="ipad">
    <div>Only hide on ipad</div>
  </ion-hide-when>

  <ion-hide-when platform="phablet">
    <div>Only hide on phablet</div>
  </ion-hide-when>

  <ion-hide-when platform="iphone">
    <div>Only hide on phone</div>
  </ion-hide-when>

  <h2>Size Tests</h2>
  <ion-hide-when size="xs">
    <div>Only hide on xs</div>
  </ion-hide-when>

  <ion-hide-when size="sm">
    <div>Only hide on sm</div>
  </ion-hide-when>

  <ion-hide-when size="md">
    <div>Only hide on md</div>
  </ion-hide-when>

  <ion-hide-when size="lg">
    <div>Only hide on lg</div>
  </ion-hide-when>

  <ion-hide-when size="xl">
    <div>Only hide on xl</div>
  </ion-hide-when>

  <ion-hide-when size="xs, m">
    <div>Only hide on XS or m</div>
  </ion-hide-when>

</ion-content>
```
