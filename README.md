# renderConfig

renderConfig = () => {
    const { header } = this.props
    return header.map(h => {
      return {
        name: h,
        dataKey: h,
      }
    })
  }
