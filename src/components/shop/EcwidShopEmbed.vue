<template>
    <div class="page__content container-xl my-8">
        <div id="my-store-96987418"></div>
        <div>
        <script data-cfasync="false" type="text/javascript" src="https://api-e.lightspeed.app/script.js?96987418&data_platform=code&data_date=2024-01-07" charset="utf-8"></script><script type="text/javascript"> xProductBrowser("categoriesPerRow=3","views=grid(20,3) list(60) table(60)","categoryView=grid","searchView=list","id=my-store-96987418");</script>
        </div>
    </div>
</template>

<!-- It looks like the issue is that you are trying to import a Vue component
directly into an Astro page. Astro does not support Vue components directly.
Here are a few options to fix this: 1. Convert the EcwidShopEmbed component to
an Astro component instead of Vue. You would need to rewrite it using Astro
features. 2. Wrap the EcwidShopEmbed component in a .vue file and import it with
Astro's vue integrator. For example: ``` // EcwidShopEmbed.vue
<script>
export default {
  // component code
};
</script>

// astro page import EcwidShopEmbed from '../components/EcwidShopEmbed.vue'; ```
3. Render the Vue component from within an Astro component using client:load
directive. For example: ``` // Astro component
<client:load component="EcwidShopEmbed" />
``` Let me know if any of those ideas help resolve the issue or if you have any
other questions!
 -->