<template lang="pug">
  footer(role="contentinfo")#links.mb0
    div.cf
      div.fl.w-100.w-third-ns.mb3.mb0-l
        h4.mb0 Information
        ul
          li.w-100
            p.mv1 email: #[a(href="mailto:hello@bernard.wang" target="_blank" alt="email") hello@bernard.wang]
          li.w-100
            p.mv1 © Bernard Wang {{ new Date().getFullYear() }}
      div.fl.w-100.w-third-ns.mb3.mb0-l
        h4.mb0 Work
        ul
          li.w-100.cf
            p.fl.mv1.w-30 Github:
            p.fl.mv1.w-70 #[a(href="https://github.com/bernardwang" target="_blank" alt="github") bernardwang]
          li.w-100.cf
            p.fl.mv1.w-30 Codepen:
            p.fl.mv1.w-70 #[a(href="https://codepen.io/bernardwang/" target="_blank" alt="codepen") bernardwang]
      div.fl.w-100.w-third-ns.mb3.mb0-l
        h4.mb0 Social
        ul
          li.w-100.cf
            p.fl.mv1.w-30 Twitter:
            p.fl.mv1.w-70 #[a(href="https://twitter.com/_bernardwang/" target="_blank" alt="twitter") _bernardwang]
          li.w-100.cf
            p.fl.mv1.w-30 LinkedIn:
            p.fl.mv1.w-70 #[a(href="https://www.linkedin.com/in/bernardwang" target="_blank" alt="linkedin") bernardwang]
    div.cf
      h4.mt6.ml-third.mb0.hl.end The end.
</template>

<script>
export default {
  name: 'ContactLinks'
}
</script>
