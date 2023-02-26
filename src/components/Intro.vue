<template>
  <div class="p-8 intro">
    <div class="blank h-16 s"></div>
    <div class="mt-10 h-40 flex flex-col items-center">
      <h1 id="title" class="title">The Future of Notes</h1>
      <div id="description" class="description text-center">
        Chronicle is a note-taking application, but more precisely it is a
        highly ustomisable knowledge base.
      </div>
    </div>
    <div class="text-center block mt-8">
      <img src="http://mikes.oss-cn-beijing.aliyuncs.com/uPic/Feb-15-2023-16-54-53.gif"
        class="w-full sm:w-7/12 text-center inline drop-shadow-lg rounded-lg" />
    </div>
  </div>
</template>

<style lang="scss">
.intro {
  #title {
    width: calc(15ch + 3px);
    animation: typing 2s steps(22), blink 0.5s step-end infinite alternate;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid;
  }

  @keyframes typing {
    from {
      width: 0;
    }
  }

  @keyframes blink {
    50% {
      border-color: transparent;
    }
  }
}
</style>
