### Framework Update (r124-r135)

#### Type Information

- Three removed all `.d.ts` files in version r126 (see [pull request](https://github.com/mrdoob/three.js/pull/21174])). All Three.js types were then moved to DefinitelyTyped (see [pull request](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/50930)).
  - [This repo](https://github.com/three-types/three-ts-types) contains all the TypeScript types for Three. Updates to this repository are then pushed to the [DefinitelyTyped repo](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/three) and which is released in the [@types/three](https://www.npmjs.com/package/@types/three) npm package.
  - As of 11/29/21, [@types/three](https://www.npmjs.com/package/@types/three) is still on version r134 and should not be expected to work fully (to check the latest version, see [here](https://github.com/three-types/three-ts-types/releases))