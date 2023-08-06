<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CGPA Calculator</title>
</head>
<body>
  <h1>CGPA Calculator</h1>
  <table>
    <tr>
      <th>Subject</th>
      <th>Credits</th>
      <th>Grade</th>
      <th>Grade Point</th>
    </tr>
    <tr>
      <td>Subject 1</td>
      <td><input type="number" id="credits1" min="1" max="5" step="0.5"></td>
      <td><input type="text" id="grade1"></td>
      <td><span id="gp1"></span></td>
    </tr>
    <tr>
      <td>Subject 2</td>
      <td><input type="number" id="credits2" min="1" max="5" step="0.5"></td>
      <td><input type="text" id="grade2"></td>
      <td><span id="gp2"></span></td>
    </tr>
    <!-- Add rows for Subject 3 to 7 similarly -->
    <!-- ... -->
    <tr>
      <td colspan="2"><button onclick="calculateCGPA()">Calculate CGPA</button></td>
      <td><span id="cgpaResult"></span></td>
    </tr>
  </table>

  <script>
    function calculateCGPA() {
      const credits = [
        parseFloat(document.getElementById("credits1").value),
        parseFloat(document.getElementById("credits2").value),
        // Add the rest of the credits for Subject 3 to 7
        // ...
      ];

      const grades = [
        document.getElementById("grade1").value.toUpperCase(),
        document.getElementById("grade2").value.toUpperCase(),
        // Add the rest of the grades for Subject 3 to 7
        // ...
      ];

      let totalCredits = 0;
      let totalGradePoints = 0;

      for (let i = 0; i < credits.length; i++) {
        if (!isNaN(credits[i]) && !isNaN(parseFloat(grades[i]))) {
          totalCredits += credits[i];
          let gradePoint = 0;
          switch (grades[i]) {
            case 'S':
              gradePoint = 10;
              break;
            case 'A':
              gradePoint = 9;
              break;
            case 'B':
              gradePoint = 8;
              break;
            case 'C':
              gradePoint = 7;
              break;
            case 'D':
              gradePoint = 6;
              break;
            case 'E':
              gradePoint = 5;
              break;
            case 'F':
              gradePoint = 0;
              break;
          }
          totalGradePoints += credits[i] * gradePoint;
          document.getElementById("gp" + (i + 1)).textContent = gradePoint;
        }
      }

      const cgpa = totalGradePoints / totalCredits;

      document.getElementById("cgpaResult").textContent = cgpa.toFixed(2);
    }
  </script>
</body>
</html>



