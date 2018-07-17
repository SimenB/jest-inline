1. run `yarn`
2. run `yarn jest` to see the test pass
3. change `toMatchSnapshot` to `toMatchInlineSanpshot`.
4. run `yarn jest -u` to update the snapshots.
5. see that while the inline snapshot is added, tho original snapshot is not cleared up
