---
layout: 'home'
hero:
  name: Auth0Vite
  tagline: Auth0, Vitepress
  actions:
    - theme: brand
      text: Guide
      link: /guide/
    - theme: alt
      text: try me
      link: /try/
---

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/donnimsifa.png',
    name: 'Donni Maulana Sifa',
    title: 'IT Healthcare Specialist',
    links: [
      { icon: 'linkedin', link: 'https://linkedin.com/in/donnimsifa' },
      { icon: 'github', link: 'https://donnimsifa.github.io' }
    ]
  }
]
</script>

<h2>Know the Dev</h2>

<VPTeamMembers size="small" :members="members" />