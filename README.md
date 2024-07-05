# Vize Final App

## Packages Used

- [React Navigation](https://reactnavigation.org/)
- [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- [React Native Reanimated](https://github.com/software-mansion/react-native-reanimated)
- [Moti](https://github.com/nandorojo/moti)
- [Nativewind](https://github.com/nativewind/nativewind)
- [Tailwindcss](https://github.com/tailwindlabs/tailwindcss)
- [React Hook Form](https://github.com/react-hook-form/react-hook-form)
- [Zod](https://github.com/colinhacks/zod)
- [React Native Gesture Handler](https://github.com/software-mansion/react-native-gesture-handler)

# Görseller

## Uygulama Varlığı

<div class="qr-container">
<a href="https://apps.apple.com/no/app/vize-final-hesaplama/id6475015751">
<img src="assets/store/1.png" alt="app store qr" />
</a>
<a href="https://play.google.com/store/apps/details?id=com.vizefinal">
<img src="assets/store/2.png" alt="play store qr" />
</a>
</div>

## ios

<div class="img-container">
  <div>
    <img src="assets/ios/1.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/ios/2.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/ios/4.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/ios/3.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>

  <div>
    <img src="assets/ios/5.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
</div>

## android

<div class="img-container">
  <div>
    <img src="assets/android/5.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/android/4.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/android/2.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/android/3.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
  <div>
    <img src="assets/android/6.png" alt="vize-final-production" style="width: 100%; height: auto;">
  </div>
</div>










<style>
 
  .img-container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 10px;
    padding: 10px;
  }
  @media (min-width: 600px) {
    .img-container {
      grid-template-columns: 1fr 1fr;
    }
  }
  @media (min-width: 900px) {
    .img-container {
      grid-template-columns: 1fr 1fr 1fr;
    }
  }
  @media (min-width: 1200px) {
    .img-container {
      grid-template-columns: 1fr 1fr 1fr 1fr;
    }
  }
  .img-container img {
    width: 100%;
    height: auto;
  }


  .qr-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-color: #fff;
    padding: 10px;
  }

  .qr-container img {
    max-width: 100%;
    height: auto;
    margin: 10px 0;
  }

  @media (min-width: 540px) {
    .qr-container {
      flex-direction: row;
      justify-content: space-around;
    }

    .qr-container img {
      margin: 0 10px;
    }
  }
</style>
