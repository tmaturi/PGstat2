## Welcome to GitHub Pages




### Sheet 1: Current Applicants5
<table class="grid" style="width: 100%">
    <caption>{{include.caption}}</caption>
    <colgroup>
        <col width="5%" />
        <col width="5%" />
      <col width="5%" />
        <col width="5%" />
         <col width="5%" />
        <col width="5%" />
      <col width="5%" />
        <col width="5%" />
         <col width="5%" />
        <col width="5%" />
      <col width="5%" />
        <col width="5%" />
         <col width="5%" />
        <col width="5%" />
      <col width="5%" />
        <col width="5%" />
        <col width="5%" />
    </colgroup>
    <thead>
        <tr class="header">
            <th>Surname</th>
            <th>Firstname</th>
            <th>Nationality</th>
            <th>Fee Status</th>
            <th>Remarks</th>
        </tr>
    </thead>
    <tbody>
     {% for student in site.data.phdstudents  %}
        {% if student.Sheet  == "Current Applicants" %}
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{  student.fee_status }} </td>
           <td>{{ student.remarks }}</td>
        </tr>
        {% endif %}
    {% endfor %}
    </tbody>
</table>

 
### Sheet 2: Live Offers
<table class="grid" style="width: 100%">
    <caption>{{include.caption}}</caption>
    <colgroup>
        <col width="25%" />
        <col width="25%" />
      <col width="25%" />
        <col width="25%" />
    </colgroup>
    <thead>
        <tr class="header">
            <th>Surname</th>
            <th>Firstname</th>
            <th>Nationality</th>
            <th>Remarks</th>
        </tr>
    </thead>
    <tbody>
     {% for student in site.data.phdstudents %}
        {% if student.Sheet  == "Live Applicants" %}
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{ student.remarks }}</td>
        </tr>
        {% endif %} 
    {% endfor %}
    </tbody>
</table>



### Sheet 3: Current Students
<table class="grid" style="width: 100%">
    <caption>{{include.caption}}</caption>
    <colgroup>
        <col width="25%" />
        <col width="25%" />
      <col width="25%" />
        <col width="25%" />
    </colgroup>
    <thead>
        <tr class="header">
            <th>Surname</th>
            <th>Firstname</th>
            <th>Nationality</th>
            <th>Remarks</th>
        </tr>
    </thead>
    <tbody>
     {% for student in site.data.phdstudents %}
        {% if student.Sheet  == "Current Students" %}
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{ student.remarks }}</td>
        </tr>
         {% endif %}
    {% endfor %}
    </tbody>
</table>
