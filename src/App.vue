<script setup>
import Bio from './components/Bio.vue'
import NewsList from './components/NewsList.vue'
import EducationList from './components/EducationList.vue'
import PublicationList from './components/PublicationList.vue'
import AwardList from './components/AwardList.vue'
import SoftwareList from './components/SoftwareList.vue'
import TalkList from './components/TalkList.vue'

</script>

<template>
  <header>
    <Bio />
    <hr>
  </header>

  <main>
    <NewsList />
    <hr>
    <EducationList />
    <PublicationList />
    <AwardList />
    <TalkList />
    <SoftwareList />
  </main>

  <footer>
    <hr>
    <p>
      Links:
      <a href="https://www.tsinghua.edu.cn/" target="_blank">Tsinghua University</a>
      | <a href="http://tns.thss.tsinghua.edu.cn/sun/" target="_blank">The System and Ubiquitous Networking Group (SUN)</a>
      | <a href="http://www.greenorbs.org/people/heyuan/" target="_blank">Dr. Yuan He</a>
    </p>
  </footer>
</template>

<style>

</style>
