<template>
<section class="sidebar sidebar_theme_light">
  <nuxt-link class="sidebar__main" to="/" exact>
    <div class="sidebar__lighting"></div>
    <svg class="sidebar__svg" width="34" height="35" fill="#C5CACD" xmlns="http://www.w3.org/2000/svg">
      <path fill-rule="evenodd" clip-rule="evenodd"
        d="M17.985 17.063V.984A.98.98 0 0017 0a.98.98 0 00-.985.984v16.079A5.006 5.006 0 0012 21.96c0 2.42 1.73 4.438 4.015 4.898v7.157A.98.98 0 0017 35a.98.98 0 00.985-.984v-7.157A5.006 5.006 0 0022 21.96a5.005 5.005 0 00-4.015-4.898zM17 24.985a3.029 3.029 0 01-3.03-3.024 3.029 3.029 0 016.06 0A3.029 3.029 0 0117 24.985zM5.985 8.812V.984A.98.98 0 005 0a.98.98 0 00-.985.984v7.828A5.006 5.006 0 000 13.71c0 2.42 1.73 4.439 4.015 4.898v15.408A.98.98 0 005 35a.98.98 0 00.985-.984V18.601A5.006 5.006 0 0010 13.703c0-2.42-1.73-4.432-4.015-4.891zM5 16.735a3.029 3.029 0 01-3.03-3.025 3.029 3.029 0 016.06 0A3.034 3.034 0 015 16.735zM29.985 8.81V.984A.98.98 0 0029 0a.98.98 0 00-.985.984V8.81A5.005 5.005 0 0024 13.707c0 2.42 1.73 4.438 4.015 4.897v15.412A.98.98 0 0029 35a.98.98 0 00.985-.984v-15.42A5.005 5.005 0 0034 13.7a4.99 4.99 0 00-4.015-4.89zM29 16.731a3.029 3.029 0 01-3.03-3.024A3.029 3.029 0 0129 10.683a3.029 3.029 0 013.03 3.024A3.029 3.029 0 0129 16.731z" />
    </svg>
  </nuxt-link>
  <nuxt-link class="sidebar__stats" to="/stats">
    <div class="sidebar__lighting"></div>
    <svg class="sidebar__svg" width="36" height="36" xmlns="http://www.w3.org/2000/svg" fill="#C5CACD">
      <path fill-rule="evenodd" clip-rule="evenodd"
        d="M5.802 18.686l5.587-5.67 1.365 1.384c.412.419 1.08.419 1.492 0l6.643-6.742v1.7c0 .59.473 1.07 1.055 1.07.583 0 1.056-.48 1.056-1.07V5.07v-.003A1.065 1.065 0 0021.944 4h-4.222c-.583 0-1.055.48-1.055 1.071 0 .592.472 1.072 1.055 1.072h1.674L13.5 12.128l-1.365-1.386a1.045 1.045 0 00-1.492 0l-6.334 6.429a1.083 1.083 0 000 1.515c.412.419 1.08.419 1.493 0zM6 31h6a1 1 0 001-1v-6a1 1 0 00-1-1H6a1 1 0 00-1 1v6a1 1 0 001 1zm1-6h4v4H7v-4zM22 17h-6c-.552 0-1 .48-1 1.071V30.93c0 .591.448 1.071 1 1.071h6c.552 0 1-.48 1-1.071V18.07C23 17.48 22.552 17 22 17zm-1 12.857h-4V19.143h4v10.714zM24.077 15.385h1.078v15.577c0 .573.482 1.038 1.077 1.038h6.536c.595 0 1.077-.465 1.077-1.038V15.385h1.078c.392 0 .754-.207.944-.538.189-.332.176-.737-.034-1.056l-5.459-8.308a1.087 1.087 0 00-.91-.483h-.003c-.37.001-.714.185-.91.488l-5.387 8.308c-.208.32-.219.723-.029 1.054.19.33.55.535.942.535zm5.393-7.396l3.495 5.319h-.197c-.595 0-1.077.465-1.077 1.038v15.577h-4.382V14.346c0-.573-.482-1.038-1.077-1.038h-.21l3.448-5.32z" />
      <path fill-rule="evenodd" clip-rule="evenodd" d="M34.945 33.89H2.11V1.056a1.055 1.055 0 00-2.109 0v33.89C0 35.528.472 36 1.055 36h33.89a1.055 1.055 0 100-2.11z" />
    </svg>
  </nuxt-link>
</section>
</template>

<script>
</script>

<style>
.sidebar {
  max-width: 72px;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border-radius: 8px 0px 0px 8px;
}

.sidebar_theme_light {
  background: #ffffff;
  box-shadow: 4px 0px 7px rgba(0, 0, 0, 0.1);
}

.nuxt-link-active .sidebar__lighting {
  background: #3591fb;
}

.nuxt-link-active .sidebar__svg {
  fill: #3591fb;
}

.sidebar__main {
  width: 72px;
  height: 35px;
  margin-bottom: 34px;
  display: flex;
  align-items: center;
}

.sidebar__stats {
  width: 72px;
  height: 36px;
  display: flex;
  align-items: center;
}

.sidebar__lighting {
  width: 4px;
  height: 24px;
  margin-right: 15px;
}
</style>
