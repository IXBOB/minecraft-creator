---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ProjectileHitEntityAfterEventSignal Class
description: Contents of the @minecraft/server.ProjectileHitEntityAfterEventSignal class.
---
# ProjectileHitEntityAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

Manages callbacks that are connected to when a projectile hits an entity.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ProjectileHitEntityAfterEvent) => void): (arg: ProjectileHitEntityAfterEvent) => void
`

Adds a callback that will be called when a projectile hits an entity.

#### **Parameters**
- **callback**: (arg: [*ProjectileHitEntityAfterEvent*](ProjectileHitEntityAfterEvent.md)) => *void*

#### **Returns** (arg: [*ProjectileHitEntityAfterEvent*](ProjectileHitEntityAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ProjectileHitEntityAfterEvent) => void): void
`

Removes a callback from being called when a projectile hits an entity.

#### **Parameters**
- **callback**: (arg: [*ProjectileHitEntityAfterEvent*](ProjectileHitEntityAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.
