<style>
  .carousel-container {
    position: relative;
    width: 100%;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
  }
  .carousel {
    display: flex;
    justify-content: flex-end;
    max-width: 600px;
    height: 100%;
    margin: 0 auto;
    position: relative;
    white-space: nowrap;
  }
  img {
    display: inline-block;
    max-width: 100%;
    height: auto;
    vertical-align: middle;
  }
  .prev, .next {
    position: absolute;
    top: 50%;
    font-size: 30px;
    font-weight: bold;
    padding: 10px;
    color: white;
    background-color: rgba(0, 0, 0, 0.5);
    cursor: pointer;
    z-index: 1;
  }
  .prev {
    left: 0;
  }
  .next {
    right: 0;
  }
</style>

<script>
  var slideIndex = 1;
  showSlides(slideIndex);

  function plusSlides(n) {
    showSlides(slideIndex += n);
  }

  function showSlides(n) {
    var i;
    var slides = document.querySelectorAll(".carousel img");
    var dots = document.querySelectorAll(".dot");
    if (n > slides.length) { slideIndex = 1 }
    if (n < 1) { slideIndex = slides.length }
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex - 1].style.display = "block";
    dots[slideIndex - 1].className += " active";
  }
</script>
# [Bánh mì `(bread)`]

## Introduction
> Vietnamese baguette, or banh mi, originated from the baguette brought to Southern Vietnam by the French in the 20th century. Some researchers believe that this dish had been present in Vietnam for 150 years. In the following decades, banh mi spread throughout Central and Southern Vietnam, especially in Saigon.

## Ingredient

## Food gallery
<div class="carousel-container">
  <div class="carousel">
    <img src="./assets/banhmi_gallery/banhmi_thitnuong.png">
    <img src="./assets/banhmi_gallery/banhmi_chalua.jpeg">
    <img src="./assets/banhmi_gallery/banhmi_bi.jpeg">
    <img src="./assets/banhmi_gallery/banhmi_dacbiet.jpeg">
    <img src="./assets/banhmi_gallery/banhmi_xiumai.jpeg">
    <img src="./assets/banhmi_gallery/banhmi_cay.jpeg">
    <img src="./assets/banhmi_gallery/banhmi_botloc.jpeg">
    <img src="./assets/banhmi_gallery/banhmi_phuong.jpeg">
  </div>
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>

## Recommended places

 - Bánh mì Phượng
<figure class="map-container">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3837.5827733488!2d108.3293479752058!3d15.878511244515282!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31420dd587dbb975%3A0xd214dd792e0869d7!2zQsOhbmggTWnMgCBQaMaw4bujbmc!5e0!3m2!1sen!2s!4v1687627500300!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</figure>

 - Bánh mì Madam Khanh
<figure class="map-container">
	<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3837.5424754189453!2d108.3253605752057!3d15.880626244459174!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31420e7943de2173%3A0x4296bf40af5321a7!2sMadam%20Khanh%20-%20The%20Banh%20Mi%20Queen!5e0!3m2!1sen!2s!4v1687628033953!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</figure>

 - Banh Mi Sum
<figure class="map-container">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3837.5594735900363!2d108.32162247518406!3d15.879734144482901!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31420e7c79a839e5%3A0x246d3ac41dde4a56!2sBanh%20Mi%20Sum!5e0!3m2!1sen!2s!4v1688192467323!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</figure>

- Bánh mì Lành
<figure class="map-container">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3837.5810129243623!2d108.329157975184!3d15.878603644512818!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31420fabb76c5089%3A0x5cb44d5942440637!2zQsOhbmggbcOsIEzDoG5o!5e0!3m2!1sen!2s!4v1688192502295!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</figure>

## Opening hours

## Price

## Reviews
