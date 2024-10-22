<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">

    <title><?= title;  ?></title>
  </head>
  <body>
    <div class="container">
      <h1><?= title;  ?></h1>

      
      <style>
        /* 圖片來源：https://hackmd.io/@ugm/SJ66fUfiU */
        /* // Extra small devices (portrait phones, less than 576px) */
        @media (max-width: 575.98px) {          
          .card-columns{
            column-count: 1;
          }
        }
        /* // Small devices (landscape phones, 576px and up) */
        @media (min-width: 576px) and (max-width: 767.98px) {         
          .card-columns{
            column-count: 2;
          }
        }
        /* // Medium devices (tablets, 768px and up) */
        @media (min-width: 768px) and (max-width: 991.98px) {         
          .card-columns{
            column-count: 3;
          }
        }
        /* // Large devices (desktops, 992px and up) */
        @media (min-width: 992px) and (max-width: 1199.98px) {         
          .card-columns{
            column-count: 3;
          }
        }
        /* // Extra large devices (large desktops, 1200px and up) */
        @media (min-width: 1200px) {         
          .card-columns{
            column-count: 3;
          }
        }
      </style> 

      <ul class="nav nav-tabs" id="myTab" role="tablist">
        <li class="nav-item">
          <a class="nav-link active" id="nav_0" data-toggle="tab" href="#content_0" role="tab" aria-controls="content_0" aria-selected="true">招牌類</a>
        </li>

        <li class="nav-item">
          <a class="nav-link" id="nav_1" data-toggle="tab" href="#content_1" role="tab" aria-controls="content_1" aria-selected="false">麵飯類</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" id="nav_2" data-toggle="tab" href="#contact_2" role="tab" aria-controls="contact_2" aria-selected="false">青菜類</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" id="nav_3" data-toggle="tab" href="#contact_3" role="tab" aria-controls="contact_3" aria-selected="false">海鮮冷盤</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" id="nav_4" data-toggle="tab" href="#contact_4" role="tab" aria-controls="contact_4" aria-selected="false">湯類</a>
        </li>
      </ul>
      
      <div class="tab-content" id="myTabContent">
        
        <div class="tab-pane fade show active" id="content_0" role="tabpanel" aria-labelledby="nav_0">          
           
          <div class="mt-5">      
            <h1 class="mt-3 mb-3 text-center">招牌</h1>
            <div class="card-columns">
              
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=1" alt="商品1">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品1</h4>
                </div>
              </div>  
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=2" alt="商品2">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品2</h4>
                </div>
              </div>   
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=3" alt="商品3">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品3</h4>
                </div>
              </div>
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=4" alt="商品4">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品4</h4>
                </div>
              </div>  
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=5" alt="商品5">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品5</h4>
                </div>
              </div> 
              
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=6" alt="商品6">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品6</h4>
                </div>
              </div>     
              
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=7" alt="商品7">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品7</h4>
                </div>
              </div>  
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=8" alt="商品8">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品8</h4>
                </div>
              </div>          
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=9" alt="商品9">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品9</h4>
                </div>
              </div>       
              
            </div>
          </div>

        </div>
        
        <div class="tab-pane fade" id="content_1" role="tabpanel" aria-labelledby="nav_1">
          
          <!-- 瀑布流 -->
          <div class="mt-5">      
            <h1 class="mt-3 mb-3 text-center">麵飯類</h1>
            <div class="card-columns">
              
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=1" alt="商品1">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品1</h4>
                </div>
              </div>  
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=2" alt="商品2">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品2</h4>
                </div>
              </div>   
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=3" alt="商品3">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品3</h4>
                </div>
              </div>
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=4" alt="商品4">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品4</h4>
                </div>
              </div>  
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=5" alt="商品5">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品5</h4>
                </div>
              </div> 
              
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=6" alt="商品6">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品6</h4>
                </div>
              </div>     
              
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=7" alt="商品7">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品7</h4>
                </div>
              </div>  
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=8" alt="商品8">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品8</h4>
                </div>
              </div>          
              <div class="card">
                <img class="card-img-top" src="https://picsum.photos/200/300?random=9" alt="商品9">
                <div class="card-body">
                  <h4 class="card-title text-center mb-0">商品9</h4>
                </div>
              </div>       
              
            </div>
          </div>

        </div>
        <div class="tab-pane fade" id="contact_2" role="tabpanel" aria-labelledby="nav_2">
          青菜類
        </div>
        <div class="tab-pane fade" id="contact_3" role="tabpanel" aria-labelledby="nav_3">
          海鮮冷盤
        </div>
        <div class="tab-pane fade" id="contact_4" role="tabpanel" aria-labelledby="nav_4">
          湯類
        </div>
      </div>
    </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js" integrity="sha384-wHAiFfRlMFy6i5SRaxvfOCifBUQy1xHdJ/yoi7FRNXMRBu5WHdZYu1hA6ZOblgut" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js" integrity="sha384-B0UglyR+jN6CkvvICOB2joaf5I4l3gm9GU6Hc1og6Ls7i6U/mkkaduKaBhlAXv9k" crossorigin="anonymous"></script>
  </body>
</html>
