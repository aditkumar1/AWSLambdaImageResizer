<h1>
Labmda Image Resizer
</h1>
<br/>

<h3>Lambda Environment variables</h3>
<code>
    buckname: "your bucket name",
    public url: "Your s3 bucket public url"
</code>

<h3>Sample request payload</h3>
<code>
    {
      "url": "your image url (can be s3 or any internet URI)",
      "width": "100",
      "height": "100"
    }
</code>
