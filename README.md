# Vowels_js
<!DOCTYPE html>
<html>
<head>
   <title></title>
<script>
// program to count the number of vowels in a string

function countVowel(str) 
{ 

    // find the count of vowels
    const count = str.match(/[aeiou]/gi).length;

    // return number of vowels
    return count;
}

// take input
const string = prompt('Enter a string: ');

const result = countVowel(string);

document.write(result);
</script>

</head>
<body>

</body>
</html>
