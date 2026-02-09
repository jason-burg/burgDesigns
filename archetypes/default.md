+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = '{{ .Date }}'
[params]
    vessel = ""
    length = ""
    status = ""
    featured = true
+++
{{< project-section reverse>}}
![Image 1](image1.png)
    This is where you type the opening paragraph
{{< /project-section >}}

{{< project-section >}}
![Image 2](image2.png)
    This is where the second paragrah goes!
{{< /project-section >}}

{{< project-section reverse >}}
![Profile drawing](test2.png)
    This is for the third paragraph
{{< /project-section >}}

{{< project-image src="image3.png" alt="Full width image" >}}
