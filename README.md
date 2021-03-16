### Slim Select

https://slimselectjs.com/

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="libs/boxicons-2.0.7/css/boxicons.min.css" />
    <link rel="stylesheet" href="libs/slimselect-1.27.0/css/slimselect.min.css" />
    <link rel="stylesheet" href="libs/bootstrap-4.6.0/css/bootstrap.min.css" />
    <title>Cardápios</title>
  </head>

  <body>
    <div class="container">
      <div class="form-group"></div>
        <label for="exampleFormControlSelect1">Example select</label>
        <select class="form-control1" id="exampleFormControlSelect1">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </div>
    </div>
    <hr class="m-3" />
    <div class="container">
      <select id="singleOptgroups">
        <optgroup label="Label 1">
          <option value="value 1">Value 1</option>
          <option value="value 2">Value 2</option>
          <option value="value 3">Value 3</option>
        </optgroup>
        <optgroup label="Label 2">
          <option value="value 21">Value 1</option>
          <option value="value 22">Value 2</option>
          <option value="value 23">Value 3</option>
        </optgroup>
      </select>
    </div>

    <hr class="m-3" />

    <!-- Options -->
    <div class="container">
      <select id="multiple" multiple>
        <option value="value 1">Value 1</option>
        <option value="value 2">Value 2</option>
        <option value="value 3">Value 3</option>
      </select>
    </div>

    <hr class="m-3" />

    <div class="container">
      <!-- Optgroups -->
    <select id="multipleOptgroups" multiple>
      <optgroup label="Label 1">
        <option value="value 1">Value 1</option>
        <option value="value 2">Value 2</option>
        <option value="value 3">Value 3</option>
      </optgroup>
      <optgroup label="Label 2">
        <option value="value 21">Value 1</option>
        <option value="value 22">Value 2</option>
        <option value="value 23">Value 3</option>
      </optgroup>
    </select>
    </div>

    <script src="libs/jquery-3.6.0/js/jquery-3.6.0.min.js"></script>
    <script src="libs/slimselect-1.27.0/js/slimselect.min.js"></script>
    <script src="libs/popper-1.16.1/js/popper.min.js"></script>
    <script src="libs/bootstrap-4.6.0/js/bootstrap.min.js"></script>
    <script src="js/main.js"></script>
  </body>
</html>

```
