<template>
  <div class="wrapper shapedividers_com-6574">
    <img id="header_img" src="../assets/common/header.png" alt="Brentyn Hanna pictured, cut off at the shoulders. 'Brentyn Hanna' floats above'." />
    <div class="social flex-center">
      <a href="https://www.linkedin.com/in/brehtyn/">
        <img
          src="../assets/common/logo_linkedin.png"
          height="40px"
          alt="Linkedin"
        />
      </a>
      <a href="https://github.com/Brehtyn">
        <img
          src="../assets/common/logo_github.png"
          height="40px"
          alt="Github"
        />
      </a>
      <a href="https://www.iBigital.com/">
        <img
          src="../assets/common/logo_simple_bigital.png"
          height="45px"
          alt="Bigital"
        />
      </a>
      <a href="https://www.instagram.com/brehtyn/">
        <img
          src="../assets/common/logo_instagram.png"
          height="40px"
          alt="Instagram"
        />
      </a>
    </div>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
}
.social {
  flex-direction: row;
  padding-top: 20px;
}
.social > a:hover {
  border-spacing: 4px;
  -moz-border-radius: 12px;
  -webkit-border-radius: 12x;
  border-radius: 12px;
  border: solid;
  border-color: var(--color-neutral);
  background: var(--color-neutral);
  transition: 0.5s;
  padding: 12px;
  padding-bottom: 4px;
  cursor: pointer;
}
.wrapper {
  height: fit-content;
  padding-bottom: 100px;
}
#header_img {
  width: 100%;
  height: auto;
  max-width: 800px;
  margin-bottom: -30px;
}
@media screen and (min-width: 768px) {
  #header_img {
    margin-left: calc(50% - 400px);
  }
}

.shapedividers_com-6574 {
  overflow: hidden;
  position: relative;
}
.shapedividers_com-6574::before {
  content: "";
  font-family: "shape divider from ShapeDividers.com";
  position: absolute;
  z-index: 3;
  pointer-events: none;
  background-repeat: no-repeat;
  bottom: -0.1vw;
  left: -0.1vw;
  right: -0.1vw;
  top: -0.1vw;
  background-size: 100% 90px;
  background-position: 50% 100%;
  background-image: url('data:image/svg+xml;charset=utf8, <svg preserveAspectRatio="xMidYMin slice" xmlns="http://www.w3.org/2000/svg" viewBox="0 -3.9 2000 95.3"><path fill="%23ffffff" d="M1859 18a6 6 0 00-7-6h-47a6 6 0 00-6 6v42a6 6 0 007 6h47a6 6 0 006-6zM1649 4a3 3 0 00-3-4l-25 1a3 3 0 00-4 3l1 22a3 3 0 003 4l25-1a3 3 0 004-3zM1468 18a6 6 0 00-7-6h-47a6 6 0 00-6 6v42a6 6 0 007 6h47a6 6 0 006-6zM1281 18a6 6 0 00-6-6h-47a6 6 0 00-7 6v42a6 6 0 007 6h47a6 6 0 007-6zM1069 6a3 3 0 00-3-2h-23a3 3 0 00-4 3l1 21a3 3 0 003 3h23a3 3 0 004-3zM889 18a6 6 0 00-7-6h-47a6 6 0 00-6 6v42a6 6 0 007 6h47a6 6 0 006-6zM694 18a6 6 0 00-7-6h-47a6 6 0 00-6 6v42a6 6 0 007 6h47a6 6 0 006-6zM487 5a3 3 0 00-3-3h-24a3 3 0 00-4 3l1 22a3 3 0 003 3h24a3 3 0 003-3zM310 18a6 6 0 00-6-6h-47a6 6 0 00-7 6v42a6 6 0 007 6h47a6 6 0 007-6zM113 18a6 6 0 00-7-6H59a6 6 0 00-6 6v42a6 6 0 007 6h47a6 6 0 006-6zM1928 8a3 3 0 00-3-3h-22a3 3 0 00-3 3v20a3 3 0 003 3l22-1a3 3 0 003-2zM1751 11a7 7 0 00-8-6h-51a7 7 0 00-8 7l1 46a7 7 0 007 7h52a7 7 0 007-7zM1556 11a7 7 0 00-7-6h-52a7 7 0 00-7 7v46a7 7 0 008 7h51a7 7 0 007-7zM1350 8a3 3 0 00-3-3h-22a3 3 0 00-3 3v19a3 3 0 003 3l22-1a3 3 0 003-2zM1172 11a7 7 0 00-7-6h-52a7 7 0 00-7 7v46a7 7 0 008 7h51a7 7 0 007-7zM977 11a7 7 0 00-7-6h-52a7 7 0 00-7 7v46a7 7 0 008 7h51a7 7 0 007-7zM764 4a3 3 0 00-3-3h-22a3 3 0 00-3 3v20a3 3 0 003 3h22a3 3 0 004-3zM590 11a7 7 0 00-8-6h-51a7 7 0 00-8 7l1 46a7 7 0 007 7h52a7 7 0 007-7zM398 11a7 7 0 00-7-6h-52a7 7 0 00-7 7v46a7 7 0 008 7h51a7 7 0 007-7zM188 4a4 4 0 00-5-4h-31a4 4 0 00-4 4v28a4 4 0 004 4h31a4 4 0 005-4z" opacity=".75"/><g opacity=".5"><path fill="%23ffffff" d="M1890 31a4 4 0 00-4-4l-30 1a4 4 0 00-4 4v29a4 4 0 005 4h29a4 4 0 004-4zM1691 31a4 4 0 00-4-4l-29 1a4 4 0 00-4 4v29a4 4 0 004 4h30a4 4 0 004-4zM1496 31a4 4 0 00-4-4l-29 1a4 4 0 00-5 4l1 29a4 4 0 004 4h29a4 4 0 005-4zM1315 31a4 4 0 00-4-4l-29 1a4 4 0 00-4 4v29a4 4 0 004 4h30a4 4 0 004-4zM1115 31a4 4 0 00-4-4l-29 1a4 4 0 00-4 4v29a4 4 0 004 4h30a4 4 0 004-4zM919 31a4 4 0 00-4-4l-30 1a4 4 0 00-4 4v29a4 4 0 005 4h29a4 4 0 004-4zM725 31a4 4 0 00-4-4l-30 1a4 4 0 00-4 4v29a4 4 0 004 4h30a4 4 0 004-4zM531 31a4 4 0 00-4-4l-30 1a4 4 0 00-4 4v29a4 4 0 004 4h30a4 4 0 004-4zM341 31a4 4 0 00-4-4l-30 1a4 4 0 00-4 4v29a4 4 0 005 4h29a4 4 0 004-4zM142 31a4 4 0 00-4-4h-30a4 4 0 00-4 5v29a4 4 0 004 4h30a4 4 0 004-4z"/></g><path fill="%23ffffff" d="M2000 95H0V49h2000z"/><path fill="%23ffffff" d="M2000 29a7 7 0 00-7-6h-50a7 7 0 00-7 6l1 45a7 7 0 007 6h49a7 7 0 007-7zM1612 25a7 7 0 00-7-6h-49a7 7 0 00-7 7v44a7 7 0 007 6h50a7 7 0 007-6zM1419 29a7 7 0 00-7-6h-50a7 7 0 00-7 6l1 45a7 7 0 007 6h49a7 7 0 007-7zM1225 29a7 7 0 00-7-6h-49a7 7 0 00-7 6v45a7 7 0 007 6h49a7 7 0 007-7zM1031 29a7 7 0 00-7-6h-49a7 7 0 00-7 6l1 45a7 7 0 006 6h50a7 7 0 007-7zM838 29a7 7 0 00-7-6h-50a7 7 0 00-6 6v45a7 7 0 007 6h49a7 7 0 007-7zM644 29a7 7 0 00-7-6h-49a7 7 0 00-7 6v45a7 7 0 007 6h50a7 7 0 006-7zM450 29a7 7 0 00-7-6h-49a7 7 0 00-7 6l1 45a7 7 0 007 6h49a7 7 0 007-7zM257 29a7 7 0 00-7-6h-50a7 7 0 00-6 6v45a7 7 0 007 6h49a7 7 0 007-7zM63 29a7 7 0 00-7-6H7a7 7 0 00-7 6v45a7 7 0 007 6h50a7 7 0 006-7zM1806 29a7 7 0 00-7-6h-49a7 7 0 00-7 6v45a7 7 0 007 6h49a7 7 0 007-7z"/></svg>');
}
</style>