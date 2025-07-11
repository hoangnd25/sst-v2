---
title: create-sst
description: "Reference docs for the create-sst CLI."
---

import MultiPackagerCode from "@site/src/components/MultiPackagerCode";
import config from "../../config";
import TabItem from "@theme/TabItem";
import HeadlineText from "@site/src/components/HeadlineText";

<HeadlineText>

A simple CLI to create new SST projects.

</HeadlineText>

---

## Usage

There's no need to install this CLI. Just use it directly to create your projects.

<MultiPackagerCode>
<TabItem value="npm">

```bash
npx create-sst@two
```

</TabItem>
<TabItem value="yarn">

```bash
yarn create sst@two
```

</TabItem>
<TabItem value="pnpm">

```bash
pnpm create sst@two
```

</TabItem>
</MultiPackagerCode>

This will prompt you for a name and bootstrap a new project in that directory.

---

## Options

Pass in the following (optional) options.

### `--template`

Instead of the standard starter, you can choose to use one of our <a href={`${config.github}//tree/master/packages/create-sst/bin/presets`}>minimal setups or examples</a> as the template to bootstrap.

<MultiPackagerCode>
<TabItem value="npm">

```bash
npx create-sst@two --template=other/go
```

</TabItem>
<TabItem value="yarn">

```bash
yarn create sst@two --template=other/go
```

</TabItem>
<TabItem value="pnpm">

```bash
pnpm create sst@two --template=other/go
```

</TabItem>
</MultiPackagerCode>

---

## Arguments

### `<destination>`

Specify a project name, instead of typing it into the interactive prompt.

<MultiPackagerCode>
<TabItem value="npm">

```bash
npx create-sst@two my-sst-app
```

</TabItem>
<TabItem value="yarn">

```bash
yarn create sst@two my-sst-app
```

</TabItem>
<TabItem value="pnpm">

```bash
pnpm create sst@two my-sst-app
```

</TabItem>
</MultiPackagerCode>
