   <?php
      $dayofweek = date("w");
      switch ($dayofweek) {
        case 1:
          echo "It is Monday!";
          echo "body {background-color: #7FFF00;}"
          break;
        case 2:
          echo "It is Tuesday!";
          echo "body {background-color: #00FFF;}"
          break;
        case 3:
          echo "It is Wednesday!";
          echo "body {background-color: 006400;}"
          break;
        case 4:
          echo "It is Thursday!";
          echo "body {background-color: #FF8C00;}"
          break;
        case 5:
          echo "It is Friday!";
          echo "#FFD700";
          break;
        case 6:
          echo "It is Saturday!";
          echo "body {background-color: #ADD8E6;}"
          break;
        case 0:
          echo "It is Sunday!";
          echo "body {background-color: #FFB6C1;}"
          break;
        default:
          echo "Error!";
          break;
      }
    ?>
