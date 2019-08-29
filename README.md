## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/tmaturi/PGstat2/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


### Sheet 1: Current Applicants
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
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{ student.remarks }}</td>
        </tr>
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
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{ student.remarks }}</td>
        </tr>
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
        <tr>
          <td>{{ student.surname }}</td>
          <td>{{ student.firstname }}</td>
          <td>{{ student.nationality }}</td>
           <td>{{ student.remarks }}</td>
        </tr>
    {% endfor %}
    </tbody>
</table>
