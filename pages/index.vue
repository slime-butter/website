<template>
  <Title>VRCD - 欢迎</Title>
  <div class="bg-[#EAEBEC] dark:bg-[#131415] pb-24 transition">
    <!--主块,竖排，-->
    <div class="sm:space-y-0 space-y-8">
      <div
        class="pt-28 min-h-screen sm:justify-center flex items-center sm:flex-row flex-col bg-center bg-no-repeat home sm:px-0 px-4">

        <div class="sm:w-3/4 mx-auto items-start gap-5 flex 2xl:flex-row flex-col">
          <div class="flex-1 space-y-14">
            <div>
              <h2 class="lg:text-6xl sm:text-5xl text-4xl font-semibold mb-2">
                虚拟现实中文开发者社区
              </h2>
              <span class="text-lg text-neutral-500">
                ————酷酷的鼠鼠
              </span>
            </div>
            <SearchBar jumpToSearch class="max-w-2xl" />
          </div>
          <div class="flex-1 sm:columns-2 columns-1 w-full *:break-inside-avoid space-y-4">
            <LinkCard class="bg-[#24C29F] text-[#24C29F]" title="开发者汉化计划" info="共同参与汉化工作，让创作无国界" target="_blank"
              href="https://wiki.vrcd.org.cn/zh/developer-localization-project" />
            <LinkCard class="bg-[#9091F7] text-[#9091F7]" title="文档库" info="公益，开源，开放的创作者知识库" target="_blank"
              href="https://docs.vrcd.org.cn/"></LinkCard>
            <LinkCard class="bg-[#35B6D6] text-[#35B6D6]" title="VPM 镜像库" info="体验更快、更便捷的 VPM 加载" target="_blank"
              href="https://vcc.vrczh.org/" />
            <LinkCard class="bg-[#24C29F] text-[#24C29F]" title="VRChat 汉化文档中心" info="VRChat 官方文档的汉化项目" target="_blank"
              href="https://docs.vrczh.org/" />
            <LinkCard class="bg-[#FFB060] text-[#FFB060]" title="VRChat 入门包" info="带你零基础学习创作的最佳途径"  target="_blank"
              href="https://docs.vrcd.org.cn/books/vrchat" />
            <LinkCard class="bg-[#BFC49F] text-[#BFC49F]" title="VRCD Wiki" info="深入了解 VRCD 和各项服务"  target="_blank"
              href="https://wiki.vrcd.org.cn/" />

          </div>
        </div>
      </div>
      <!--简介-->
      <div class="sm:w-3/4 mx-auto flex flex-col p-6 space-y-4 rounded-lg bg-zinc-100/40 dark:bg-zinc-900/70">
        <h2 class="rounded-lg text-3xl font-semibold">
          简介
        </h2>
        <div class="text-base font-normal">
          <p>
            虚拟现实中文开发者社区（Virtual Reality Chinese Developer）是一个刚刚起步的面向玩家，初高级开发者，内容创作者的共创开源社区，在这里，您可以找到一众优秀的 VR
            内容创作者与热心好学的新兴创作力量。
          </p>
          <p>
            VRCD 为新手提供必要的入门资源，为创作者们提供创作扶持，让大家获得更丰富和谐的内容创作环境。
          </p>
          <p>
            与此同时，VRCD 也提供与众不同的，精彩的创作者活动和资讯，例如来自 VRChat 官方的最新资讯和活动，您也可以在这里参与汉化相关的活动，如 VRChat 开发者汉化，VR
            文档汉化等，让您可以为 VR 的中文化做出贡献，以享受更多的 VR 内容。
          </p>
          <p>
            VRCD 欢迎您的加入，让我们一起参加活动，共同推动社区发展！您的帮助和支持也许会带来意想不到的影响和效果！
          </p>
        </div>
        <div class="flex md:flex-row flex-col space-x-0 md:space-x-4 space-y-4 md:space-y-0">
          <div class="flex-auto">
            <NuxtPicture :imgAttrs="{ class: 'size-full rounded-md object-cover' }" src="/images/home/home-1.png" />
          </div>
          <div class="flex-auto">
            <NuxtPicture :imgAttrs="{ class: 'size-full rounded-md object-cover' }" src="/images/home/home-2.jpg" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.home {
  background-image: url('/images/home/background-cover.png');
}

.banner {
  background-image: url('/images/home/banner.png');
}
</style>
