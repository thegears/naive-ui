<markdown>
# Ignore gap
</markdown>

<template>
  <div style="height: 200px">
    <n-row :gutter="12">
      <n-col :span="6">
        <div />
      </n-col>
      <n-col :span="6">
        <div />
      </n-col>
      <n-col :span="6">
        <div style="width: 160px">
          <n-anchor
            affix
            :trigger-top="24"
            :top="88"
            style="z-index: 1"
            ignore-gap
          >
            <n-anchor-link title="Demos" href="#Demos">
              <n-anchor-link title="Ignore-Gap" href="#ignore-gap" />
              <n-anchor-link title="Affix" href="#affix" />
              <n-anchor-link title="Scroll To" href="#scrollto" />
            </n-anchor-link>
            <n-anchor-link title="Props" href="#Props" />
          </n-anchor>
        </div>
      </n-col>
      <n-col :span="6">
        <div style="width: 160px">
          <n-anchor affix :trigger-top="24" :top="88" style="z-index: 1">
            <n-anchor-link title="Demos" href="#Demos">
              <n-anchor-link title="Ignore-Gap" href="#ignore-gap" />
              <n-anchor-link title="Affix" href="#affix" />
              <n-anchor-link title="Scroll To" href="#scrollto" />
            </n-anchor-link>
            <n-anchor-link title="Props" href="#Props" />
          </n-anchor>
        </div>
      </n-col>
    </n-row>
  </div>
</template>
