## Welcome to GitHub Pages




### Sheet 1: Current Applicants
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
      <col width="20%" />
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
            <th>Date Applied</th>
            <th>Degree</th>
            <th>Subgroup</th>
            <th>Status</th>
            <th>PT/FT</th>
            <th>Funding</th>
            <th>Remarks</th>
            <th>Supervisor I</th>
            <th>Supervisor II</th>
            <th>Offer start date</th>
            <th>First deferral</th>
            <th>Second deferral</th>
            <th>Revoked</th>
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
           <td>{{ student.date_applied }}</td>
             <td>{{ student.degree }}</td>
          <td>{{ student.subgroup }}</td>
          <td>{{ student.status }}</td>
           <td>{{  student.PT_FT }} </td>
           <td>{{ student.funding }}</td>
             <td>{{ student.remarks }}</td>
          <td>{{ student.supervisor_I }}</td>
          <td>{{ student.supervisor_II }}</td>
           <td>{{  student.offer_start_date }} </td>
           <td>{{ student.first_deferral }}</td>
             <td>{{ student.second_deferral }}</td>
             <td>{{ student.revoked }}</td>
        </tr>
        {% endif %}
    {% endfor %}
    </tbody>
</table>

 
### Sheet 2: Live Offers
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
      <col width="20%" />
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
            <th>Date Applied</th>
            <th>Degree</th>
            <th>Subgroup</th>
            <th>Status</th>
            <th>PT/FT</th>
            <th>Funding</th>
            <th>Remarks</th>
            <th>Supervisor I</th>
            <th>Supervisor II</th>
            <th>Offer start date</th>
            <th>First deferral</th>
            <th>Second deferral</th>
            <th>Revoked</th>
        </tr>
    </thead>
    <tbody>
     {% for student in site.data.phdstudents %}
        {% if student.Sheet  == "Live Applicants" %}
        <tr>
           <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{  student.fee_status }} </td>
           <td>{{ student.date_applied }}</td>
             <td>{{ student.degree }}</td>
          <td>{{ student.subgroup }}</td>
          <td>{{ student.status }}</td>
           <td>{{  student.PT_FT }} </td>
           <td>{{ student.funding }}</td>
             <td>{{ student.remarks }}</td>
          <td>{{ student.supervisor_I }}</td>
          <td>{{ student.supervisor_II }}</td>
           <td>{{  student.offer_start_date }} </td>
           <td>{{ student.first_deferral }}</td>
             <td>{{ student.second_deferral }}</td>
             <td>{{ student.revoked }}</td>
        </tr>
        {% endif %} 
    {% endfor %}
    </tbody>
</table>



### Sheet 3: Current Students
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
      <col width="20%" />
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
            <th>Date Applied</th>
            <th>Degree</th>
            <th>Subgroup</th>
            <th>Status</th>
            <th>PT/FT</th>
            <th>Funding</th>
            <th>Remarks</th>
            <th>Supervisor I</th>
            <th>Supervisor II</th>
            <th>Offer start date</th>
            <th>First deferral</th>
            <th>Second deferral</th>
            <th>Revoked</th>
        </tr>
    </thead>
    <tbody>
     {% for student in site.data.phdstudents %}
        {% if student.Sheet  == "Current Students" %}
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{  student.fee_status }} </td>
           <td>{{ student.date_applied }}</td>
             <td>{{ student.degree }}</td>
          <td>{{ student.subgroup }}</td>
          <td>{{ student.status }}</td>
           <td>{{  student.PT_FT }} </td>
           <td>{{ student.funding }}</td>
             <td>{{ student.remarks }}</td>
          <td>{{ student.supervisor_I }}</td>
          <td>{{ student.supervisor_II }}</td>
           <td>{{  student.offer_start_date }} </td>
           <td>{{ student.first_deferral }}</td>
             <td>{{ student.second_deferral }}</td>
             <td>{{ student.revoked }}</td>
        </tr>
         {% endif %}
    {% endfor %}
    </tbody>
</table>
