# create-HTML-table-
<!-- Lab 1-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Mark Sheet</title>
  <style>
    table {
      width: 80%;
      border-collapse: collapse;
      margin: 20px auto;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    th, td {
      border: 1px solid #000;
      padding: 10px;
    }

    th:nth-child(odd), td:nth-child(odd) {
      background-color: #d9eaff; /* Light blue */
    }

    th:nth-child(even), td:nth-child(even) {
      background-color: #ffffff; /* White */
    }

    th {
      background-color: #cce0ff;
    }

    caption {
      caption-side: top;
      font-size: 1.5em;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <table>
    <caption>Student Mark Sheet</caption>
    <tr>
      <th>Name</th>
      <th>Maths</th>
      <th>Science</th>
      <th>English</th>
      <th>Physics</th>
      <th>General Knowledge</th>
    </tr>
    <tr>
      <td>Anil Kumar</td>
      <td>49</td>
      <td>69</td>
      <td>79</td>
      <td>67</td>
      <td>78</td>
    </tr>
    <tr>
      <td>Sunil Kumar</td>
      <td>39</td>
      <td>59</td>
      <td>89</td>
      <td>47</td>
      <td>48</td>
    </tr>
    <tr>
      <td>Rakesh Sharma</td>
      <td>46</td>
      <td>68</td>
      <td>73</td>
      <td>62</td>
      <td>78</td>
    </tr>
    <tr>
      <td>Farida Khan</td>
      <td>89</td>
      <td>59</td>
      <td>69</td>
      <td>57</td>
      <td>88</td>
    </tr>
  </table>
</body>
</html>
