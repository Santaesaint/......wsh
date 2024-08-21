new Tether({
  element: yellowBox,
  target: greenBox,
  attachment: 'top left',
  targetAttachment: 'bottom left'
});new Tether({
  element: yellowBox,
  target: greenBox,
  attachment: 'top left',
  targetAttachment: 'bottom left',
  optimizations: {
    moveElement: false
  }
});new Tether({
  element: yellowBox,
  target: greenBox,
  attachment: 'top left',
  optimizations: {
    gpu: false
  }
});
