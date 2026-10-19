<svg
    class="flowers"
    aria-hidden="true"
    viewBox="0 0 414 896"
    preserveAspectRatio="xMidYMid slice"
  >
    <defs>
      <g id="bloom">
        <ellipse cx="0" cy="-17" rx="10" ry="17" />
        <ellipse cx="0" cy="-17" rx="10" ry="17" transform="rotate(72)" />
        <ellipse cx="0" cy="-17" rx="10" ry="17" transform="rotate(144)" />
        <ellipse cx="0" cy="-17" rx="10" ry="17" transform="rotate(216)" />
        <ellipse cx="0" cy="-17" rx="10" ry="17" transform="rotate(288)" />
        <circle r="5" fill="#ffffff" fill-opacity="0.75" />
      </g>
      <path id="leaf" d="M0 0 C 12 -14 30 -14 42 0 C 30 14 12 14 0 0 Z" />
    </defs>

    <!-- prawy górny róg -->
    <use href="#leaf" transform="translate(300 30) rotate(150) scale(1.4)" fill="#cfe6d6" opacity="0.55" />
    <use href="#leaf" transform="translate(414 120) rotate(110) scale(1.2)" fill="#cfe6d6" opacity="0.5" />
    <use href="#bloom" transform="translate(386 44) scale(3.3) rotate(12)" fill="#f4a9c3" opacity="0.4" />
    <use href="#bloom" transform="translate(318 -4) scale(2.1) rotate(40)" fill="#f7bfd3" opacity="0.45" />
    <use href="#bloom" transform="translate(408 150) scale(1.5) rotate(-20)" fill="#f4a9c3" opacity="0.35" />

    <!-- lewy dolny róg -->
    <use href="#leaf" transform="translate(70 840) rotate(-40) scale(1.5)" fill="#cfe6d6" opacity="0.55" />
    <use href="#leaf" transform="translate(-6 730) rotate(-70) scale(1.3)" fill="#cfe6d6" opacity="0.5" />
    <use href="#bloom" transform="translate(22 858) scale(3.4) rotate(-8)" fill="#f4a9c3" opacity="0.4" />
    <use href="#bloom" transform="translate(104 910) scale(2.2) rotate(25)" fill="#f7bfd3" opacity="0.45" />
    <use href="#bloom" transform="translate(-4 772) scale(1.8) rotate(50)" fill="#f4a9c3" opacity="0.35" />

    <!-- mały kwiatek przy prawej krawędzi -->
    <use href="#bloom" transform="translate(402 600) scale(1.3) rotate(5)" fill="#f7bfd3" opacity="0.4" />
  </svg>


<style scoped>
.flowers {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
}
</style>
