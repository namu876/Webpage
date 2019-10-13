# Webpage
A simple webpage
Please write some code of the webpage.
<!DOCTYPE html>
<html>
<head>
	<title> hello world
	</title>
	<script type="text/javascript" src="button1.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

</head>
<body>
	<script src="http://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>

<button type="button" onclick="promptMe()" id="myButton" data-loading-text="Loading..." class="btn btn-primary" autocomplete="off">
  Loading state
</button>

<script>
        function goPython(){
            $.ajax({
              url: "pygame1.py",
             context: document.body
            }).done(function() {
             alert('finished python script');;
            });
        }
    </script>


</body>
</html>

like this
