<template>
  <div></div>
</template>

<script>
export default {
  props: ['c'],
  // data () {
  //   return {
  //     wx:window.innerWidth*0.98,
  //     wy:window.innerHeight*0.94,
  //     circle_x: 30+(Math.random()*100),
  //     circle_y: 30+(Math.random()*100),
  //     dx: 1+ Math.floor(Math.random() * (Math.random()*10)),
  //     dy: 1+ Math.floor(Math.random() * (Math.random()*10)),
  //     radius: 30,
  //   }
  // },
  // watch: {
  //   circle_x: function(value) {
  //     this.dx = value > this.wx-this.radius ? this.dx*-1 : this.dx;
  //     this.dx = value < this.radius ? this.dx*-1 : this.dx;
  //   },
  //   circle_y: function(value) {
  //     this.dy = value > this.wy-this.radius ? this.dy*-1 : this.dy;
  //     this.dy = value < this.radius ? this.dy*-1 : this.dy;
  //   }
  // },
  // methods: {
  //   animate() {
  //     requestAnimationFrame(this.animate)
  //     this.goStraight()
  //   },
  //   // 直進
  //   goStraight() {
  //     this.c.clearRect(0, 0, this.wx, this.wy)
  //     // this.c.clearRect(this.circle_x-35, this.circle_y-35, 75, 75)
  //     this.drawCircle2()
  //     this.circle_x+=this.dx;
  //     this.circle_y+=this.dy;
  //   },
  //   drawCircle2() {
  //     this.c.beginPath()
  //     this.c.arc(this.circle_x, this.circle_y, this.radius, 0, Math.PI * 2)
  //     this.c.fillStyle = '#DC7FAE'
  //     this.c.strokeStyle = '#DC7FAE'
  //     this.c.fill()
  //     // this.c.stroke()
  //   },
  // },
  mounted () {
    console.log(this.c)
    // this.c = this.$el.getContext('2d', { alpha: true })
    // this.$el.width = this.wx;
    // this.$el.height = this.wy;
    // this.drawCircle2()
    // this.animate()
  }
}

</script>

<style scoped>
  canvas {
    /* background: #efefef; */
  }
</style>
