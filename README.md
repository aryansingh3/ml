Plot.plot({
  marks: [
    Plot.lineY(iters, {
      x: "iter",
      y: "loss"
    }),
    Plot.ruleY([0])
  ]
})
