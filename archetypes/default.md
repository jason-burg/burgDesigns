+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = '{{ .Date }}'
[params]
    vessel = ""
    length = ""
    status = ""
    featured = true
+++

{{< project-section img="image1.png" alt="Image1" rev="true" cap="Image1" >}}
    This is where you type the opening paragraph
{{< /project-section >}}

{{< project-section img="image2.png" alt="Image2" rev="true" cap="Image2" >}}
    This is where the second paragrah goes!
{{< /project-section >}}

{{< project-section img="image3.png" alt="Image3" rev="true" cap="Image3" >}}
    This is for the third paragraph
{{< /project-section >}}

{{< project-image src="image3.png" alt="Full width image" >}}
