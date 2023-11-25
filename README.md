# Trim PDF

### Tech stack used :
<div>
<img src="https://logos-world.net/wp-content/uploads/2023/08/React-Symbol.png" title="React" alt="React" width="100" height="60"/>&nbsp;
<img src="https://getlogovector.com/wp-content/uploads/2021/01/tailwind-css-logo-vector.png" title="TailwindCSS" alt="TailwindCSS" width="120" height="60"/>&nbsp;
<img src="https://cdn.freebiesupply.com/logos/large/2x/nodejs-logo-svg-vector.svg" title="NodeJS" alt="NodeJS" width="100" height="50"/>&nbsp;
<img src="https://user-images.githubusercontent.com/46530103/149555718-00be7ed3-3c62-42e4-a9af-cf11845a4e4d.jpg" title="Express.js" alt="Express.js" width="160" height="60"/>&nbsp;
</div>
<br/>  <br/>

**Trim PDF** is a full-stack web application designed to extract specific pages from uploaded PDF files. With an intuitive user interface, users can easily upload PDFs, select desired pages, and generate a new downloadable PDF tailored to their needs. Leveraging React.js for the front end and Node.js/Express.js for the back end, the application ensures efficient processing, even with large files. This project not only demonstrates my proficiency in full-stack development but also addresses a practical need, offering a time-saving and customizable solution for users dealing with multi-page PDFs.

### Have a look at individual 'frontend' and 'backend' ReadMe file for more info on how to set them up!

I'm using IronPDF library to remove pages from original PDF file. This library is not free of cost and thus gives a watermark in the converted PDF file. This watermark can be removed by purchasing a licence of their library. Alternatively, some other library could also be used.

## Screenshots

1. Home page ![Home page](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/1.png)
2. After clicking on 'choose file' ![](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/2.png)
3. File is uploaded ![](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/3.png)
4. After clicking on 'view pdf' a preview of all pages of pdf is shows ![](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/4.png)
5. If user tries to download pdf without selecting any pages, it shows an error message ![](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/5.png)
6. After selecting atleast 1 page and clicking on 'download new pdf' button, user gets prompt to download new file ![](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/6.png)
7. Api calls to the backend ![](https://github.com/piyushdahiya1218/pdf-extractor/blob/master/assets/readmeImages/7.png)
