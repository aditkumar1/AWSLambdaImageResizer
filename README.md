<h1>
Labmda Image Resizer
</h1>
<br/>

<h3>Lambda Environment variables</h3>
<code><br/>
    buckname: your bucket name<br/>
    public url: Your s3 bucket public url
</code>

<h3>Sample request payload</h3>
<code><br/>
    {<br/>
      "url": "your image url (can be s3 or any internet URI)",<br/>
      "width": "100",<br/>
      "height": "100"<br/>
    }
</code>