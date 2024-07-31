<template>
  <div class="flex flex-col gap-4">
    <div class="border border-solid border-gray/10 p4 rounded-lg mt-20">
      <p>
        Custom icons from local fs:
        <Icon
          name="custom1:nuxt-v1"
          size="64"
        />
        <Icon
          name="custom1:nuxt-v2"
          size="64"
        />
        <Icon
          name="custom1:nuxt-v3-beta"
          size="64"
        />
        <Icon
          name="custom1:nuxt-v3"
          size="64"
        />

        <!-- Workaround, load at least single icon in css mode to make svg work when set via app.config.ts -->
        <!-- comment this one out and all above disappear -->
        <Icon
          style="display: none;"
          name="custom1:nuxt-v3"
          size="64"
          mode="css"
        />
      </p>
    </div>
  </div>
</template>
