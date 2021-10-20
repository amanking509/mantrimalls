
<!DOCTYPE html>
<html lang="en">
<head>
  <title>MantriMall</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <style>
       .rounded{
          border-radius: 30px !important;
      }
      .border-0{
        border: none  !important;
      }
      @media(max-width:767px){
        .w-sm-100{
            width: 100% !important;
        }
      }
  </style>
</head>
<body>
  <div class="modal" id="loader">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content bg-transparent border-0">
  
        <!-- Modal Header -->
      
  
        <!-- Modal body -->
        <div class="modal-body bg-transparent text-center">
            <img src="img/loader.gif" class="img-fluid mx-auto" />
        </div>
  
        <!-- Modal footer -->
    
  
      </div>
    </div>
  </div>
<nav class="navbar navbar-expand-sm bg-primary navbar-dark">
    <ul class="navbar-nav">
        <li class="nav-item active">
            <a class="nav-link h2" href="#">Login</a>
        </li>
    </ul>
</nav>
<div class="container">
  <div class="w-50 mx-auto mt-5 w-sm-100">
    <form action="index.php" method="post">
        <div class="form-group mb-3">
            <input type="tel" class="form-control rounded" maxlength="10" name="phone_no" placeholder="Enter Your Number" required />
          
        </div>
        <div class="form-group">
            <input type="password" class="form-control rounded" name="password" placeholder="Enter Your Password" required />
        </div>
        <div class="form-group form-check">
          <label class="form-check-label ml-3">
            <input class="form-check-input" type="checkbox" name="remember"> Remember me
          </label>
        </div>
        <button data-target="#loader" data-toggle="modal" type="submit" name="Submit" class="btn btn-primary mx-auto d-block px-5">Login</button>
      </form>
  </div>
  
</div>

</body>
</html>
