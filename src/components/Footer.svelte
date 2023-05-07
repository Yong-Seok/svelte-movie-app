<footer>
    <div>
        <a href="https://github.com/Yong-Seok/svelte-movie-app.git">GitHub Repo.</a>
    </div>

    <div>
        <a href="https://github.com/Yong-Seok/svelte-movie-app.git">
            @{new Date().getFullYear()}
            Ethan
        </a>
    </div>
</footer>

<style lang="scss">
    footer {
      padding: 70px;
      text-align: center;
      a {
        color: $color--white-10;
        text-decoration: none;
        &.hover {
          text-decoration: underline;
        }
      }
    }
</style>