 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
</head>
<body>
   <div class="container">
    <h2> form demo </h2>
    <form >
      <div class="row">
        <div class="mb-3 col">
          <label for="email" class="form-label"> email </label>
          <input type="text" class="form-control" placeholder="email" id="email">
        </div>
         <div class="mb-3 col">
          <label for="password" class="form-label"> password </label>
          <input type="password" class="form-control" placeholder="password" id="password">
         </div>
      </div>
        <div>
          <label for="adress" class="form-label">adress  </label>
          <input 
          type="text" 
          class="form-control"
           placeholder="adress" 
           id="adress">
        </div>
        <div class=" mb-3">
          <select class="form-select" >
            <option selected> choose your city</option>
            <option value="1">pune </option>
            <option value="2">muzfaarpur</option>
            <option value="3">delhi</option>
          </select>
        </div>
        <div  class="mb-3 form-check">
          <label for="agreebs" class="form-check-label">agree</label>
          <input type="checkbox" id="agreebs" class="form-check-input">
        </div>
        <div class="form-check form-switch mb-3">
          <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
          <label class="form-check-label" for="flexSwitchCheckDefault">Default switch checkbox input</label>
        </div>
        
    </form>
   </div>
    
</body>
</html>
