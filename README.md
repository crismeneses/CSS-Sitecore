/* -- COPY or EDIT CSS IN HOMEPAGE "" --*/
/* adjust image to the carousel and text-box */
.image-carousel .image-carousel-item{
    max-width:200%;
}
.image-carousel .image-carousel-item .imgc-box-holder {
    position: absolute;
    bottom: 100px;
    top: 100px;
    right: 2px;
    height: auto;
    width: 100%;
    background: rgba(244, 243, 239, 0.83);
  }
.image-carousel .image-carousel-item .imgc-box {
    padding: 30px;
    position: relative;
    padding-top: initial;
    padding-bottom: initial;
}
.image-carousel .bx-wrapper .bx-controls .bx-pager .bx-pager-item a.bx-pager-link {
    display: block;
    margin: 0 7px 0 7px;
    height: 16px;
    width: 16px;
    border-radius: 8px;
    background: #e1ded8;
    text-decoration: none;
    text-indent: -99999px;
}
.image-carousel .image-carousel-item .imgc-box .imgc-box-content {
    padding: 1px 0 0 0;
    font: normal normal 300 16px/23px "Roboto",sans-serif;
    color: #444;
}
h2 {
    font: normal normal normal 50px/57px "Abel", sans-serif;
    color: #444;
    margin: 0;
    padding: 5px 10px 30px 0px;
}
img {
    width: 100%;
    height: 100%;
}
/* Title logo Simplisima ajust*/
.img-sim{
    width: 50%;
    height: 50%;
}
/* Align Footer Logo and Etex-bar*/
.etex-footer {
    margin: 1px 0 0 0;
    height: 40px;
    position: relative;
}
.etex-footer::before {
    content: ' ';
    display: block;
    width: 85px;
    height: 104px;
    bottom: 60px;
    left: 0;
  }
/* Responsive view*/
@media 
only screen and (max-width: 760px),
(min-device-width: 768px) and (max-device-width: 1024px)  {
  /* Hide the text-box and titles*/
  h1.imgc-overlay-title {
    display: none;
  }
  .imgc-overlay-subtitle{
      display: none;
  }
  /* -- if you want to display the text-box --
  img {
    width: auto;
    height: 70%;
    text-align: center;
  }
  .img-sim{
    width: 100%;
    height: 100%;
  }
  h2 {
    font: normal normal normal 23px/27px "Abel", sans-serif;
    color: #444;
    margin: 0;
    padding: 5px 10px 10px 0px;
  }
  .image-carousel .image-carousel-item .imgc-box-holder {
    display: none;
    position: absolute;
    bottom: 20px;
    top: 1px;
    right: 2px;
    width: 60%;
    heigth: 50%;
    max-width: 100%;
    background: rgba(189,189,189,0.80);    
  }*/
  
  /* Adjust footer logo responsive*/
  .etex-footer::before {
    display: block;
    width: 85px;
    height: 104px;
    top: -380%;
    float: right;
    position: relative;
    padding-right: 20px;
  }
  /* Adjust location search responsive*/
  .location-intro-search input, .cta-search .content .form-control input {
    display: block;
    margin: -30px 0;
  }
}





/* -- COPY or EDIT CSS PAGES --*/
/* auto adjust image to the top banner pages*/
img {
    width: 100%;
    height: auto;
    max-width: 200%;
}
/* Hide box-holder of banner */
.image-carousel .image-carousel-item .imgc-box-holder {
    background: rgba(204, 204, 204, 0);
}

