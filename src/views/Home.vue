<template>
  <div class="home">
    <p>
      <font-awesome-icon icon="apple-alt" style="color:red" />
    </p>
    <p>
      <span>Size:</span>
      <font-awesome-icon :icon="['fab', 'apple']" size="xs" />
      <font-awesome-icon :icon="['fab', 'apple']" size="lg" />
      <font-awesome-icon :icon="['fab', 'apple']" size="6x" />
    </p>
    <p>
      <span>Fixed width:</span>
      <font-awesome-icon icon="spinner" fixed-width />
    </p>
    <p>
      <span>Flip horizontally, vertically, or both:</span>
      <font-awesome-icon icon="spinner" flip="horizontal" />
      <font-awesome-icon icon="spinner" flip="vertical" />
      <font-awesome-icon icon="spinner" flip="both" />
    </p>
    <p>
      <span>spin, pulse</span>
      <font-awesome-icon icon="spinner" spin />
      <font-awesome-icon icon="spinner" pulse />
    </p>
    <p>
      <span>Border</span>
      <font-awesome-icon icon="spinner" border />
    </p>
    <p>
      <span>Pull left or right:</span>
      <font-awesome-icon icon="spinner" pull="left" />
      <font-awesome-icon icon="spinner" pull="right" />
    </p>
    <p>
      <span>Powet Transforms</span>
      <font-awesome-icon icon="spinner" transform="shrink-6 left-4" />
      <font-awesome-icon icon="spinner" :transform="{ rotate: 42 }" />
    </p>
    <p>
      <span>Masking</span>
      <font-awesome-icon icon="coffee" :mask="['fas', 'circle']" />
    </p>
    <p>
      <span>Use i tag to load icon</span>
      <i class="fas fa-coffee"></i>
    </p>
  </div>
</template>
