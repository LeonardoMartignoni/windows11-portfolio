<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <div class="window-dropdown flex items-center">
    <svg stroke="currentColor" fill="#2e2e2e" stroke-width="0" viewBox="0 0 24 24" height="1.5rem" width="1.5rem" xmlns="http://www.w3.org/2000/svg">
      <g>
        <path fill="none" d="M0 0h24v24H0z"></path>
        <path d="M12 15l-4.243-4.243 1.415-1.414L12 12.172l2.828-2.829 1.415 1.414z"></path>
      </g>
    </svg>
    <h3 class="text-base font-light whitespace-nowrap ml-1 mr-4">{{ $t("this-pc.folders") }} (6)</h3>
    <hr class="w-full" />
  </div>

  <div class="window-dropdown-content grid grid-cols-3">
    <router-link :to="{ name: 'desktop-explorer' }" class="folder">
      <div class="folder-content flex">
        <img src="/images/quickaccess/desktop.png" />
        <div class="folder-details flex flex-col">
          <span>{{ $t("explorer.desktop") }}</span>
          <span>{{ $t("explorer.this-pc") }}</span>
          <svg stroke="currentColor" fill="gray" stroke-width="0" viewBox="0 0 16 16" height=".75rem" width=".75rem" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"></path>
          </svg>
        </div>
      </div>
    </router-link>
    <router-link :to="{ name: 'downloads' }" class="folder">
      <div class="folder-content flex">
        <img src="/images/quickaccess/downloads.png" />
        <div class="folder-details flex flex-col">
          <span>{{ $t("explorer.downloads") }}</span>
          <span>{{ $t("explorer.this-pc") }}</span>
          <svg stroke="currentColor" fill="gray" stroke-width="0" viewBox="0 0 16 16" height=".75rem" width=".75rem" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"></path>
          </svg>
        </div>
      </div>
    </router-link>
    <router-link :to="{ name: 'documents' }" class="folder">
      <div class="folder-content flex">
        <img src="/images/quickaccess/documents.png" />
        <div class="folder-details flex flex-col">
          <span>{{ $t("explorer.documents") }}</span>
          <span>{{ $t("explorer.this-pc") }}</span>
          <svg stroke="currentColor" fill="gray" stroke-width="0" viewBox="0 0 16 16" height=".75rem" width=".75rem" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"></path>
          </svg>
        </div>
      </div>
    </router-link>
    <router-link :to="{ name: 'pictures' }" class="folder">
      <div class="folder-content flex">
        <img src="/images/quickaccess/pictures.png" />
        <div class="folder-details flex flex-col">
          <span>{{ $t("explorer.pictures") }}</span>
          <span>{{ $t("explorer.this-pc") }}</span>
          <svg stroke="currentColor" fill="gray" stroke-width="0" viewBox="0 0 16 16" height=".75rem" width=".75rem" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"></path>
          </svg>
        </div>
      </div>
    </router-link>
    <router-link :to="{ name: 'videos' }" class="folder">
      <div class="folder-content flex">
        <img src="/images/quickaccess/videos.png" />
        <div class="folder-details flex flex-col">
          <span>{{ $t("explorer.videos") }}</span>
          <span>{{ $t("explorer.this-pc") }}</span>
          <svg stroke="currentColor" fill="gray" stroke-width="0" viewBox="0 0 16 16" height=".75rem" width=".75rem" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"></path>
          </svg>
        </div>
      </div>
    </router-link>
    <router-link :to="{ name: 'music' }" class="folder">
      <div class="folder-content flex">
        <img src="/images/quickaccess/music.png" />
        <div class="folder-details flex flex-col">
          <span>{{ $t("explorer.music") }}</span>
          <span>{{ $t("explorer.this-pc") }}</span>
          <svg stroke="currentColor" fill="gray" stroke-width="0" viewBox="0 0 16 16" height=".75rem" width=".75rem" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"></path>
          </svg>
        </div>
      </div>
    </router-link>
  </div>
</template>

<style lang="scss" scoped>
.window-dropdown {
  margin-top: 20px;
  margin-bottom: 8px;
  hr {
    border-color: #2e2e2e;
  }
}

.window-dropdown-content {
  row-gap: 12px;
  column-gap: 20px;
  margin: 0 20px;

  .folder {
    .folder-content {
      padding: 5px 5px;
      &:hover {
        border-radius: 5px;
        background-color: #2e2e2e;
      }

      & > img {
        width: 50px;
      }

      .folder-details {
        margin-left: 5px;
      }
    }
  }
}
</style>
