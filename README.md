<!DOCTYPE html>
<html>
<body>
<h1>MĀJASDARBS ANGĻU VALODAI</h1>
<p>Pirms piekļuves mājasdarbam lūdzu izpildiet doto captchu.</p>

<form id="myForm">
    <input  type="text" name="foo" required />

    <button type="submit"> Submit </button>

</form>

<script>
    $("#myForm").on('submit',function(){
        console.log("I'm entering the submit event handler");
    });
</script>


</body>
</html>
