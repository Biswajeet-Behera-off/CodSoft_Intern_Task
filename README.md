# *Data Science_Intern_Task_at CodSoft*
<!DOCTYPE html>
<html>
<head>
    <title>PDF Viewer</title>
    <style>
        #pdf-viewer {
            width: 90%;
        }
    </style>
</head>
<body>
    <iframe id="pdf-viewer" src="https://github.com/Biswajeet-Behera-off/CodSoft_Intern_Task/blob/main/TaskDetails.pdf"></iframe>

    <script>
        // Get the PDF URL from the query string
        const queryString = window.location.search;
        const urlParams = new URLSearchParams(queryString);
        const pdfUrl = urlParams.get('pdf');

        // Set the iframe source to the PDF URL
        const pdfViewer = document.getElementById('pdf-viewer');
        pdfViewer.src = pdfUrl;
    </script>
</body>
</html>
