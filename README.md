# 🦚

## Ts-Curves

#### Just input the progress and get your curve, it's that simple. as well keep in mind that _progess is inbetween **0 to 1**._

### Features

- Typescript Intellisense

- Include definations for most of easing curves, So you would not need to check browser for what does this curve do,

![image](https://user-images.githubusercontent.com/69889565/182584715-9d2e8499-f632-4124-8884-522b9b4bbf86.png)

## Mention

- Most of the Curves Taken from flutter Official repo [link](https://github.com/flutter/flutter/blob/master/packages/flutter/lib/src/animation/curves.dart)

# Curves

## DecelerateCurve: Decelerate()

### A curve where the rate of change starts out quickly and then decelerates; an upside-down `f(t) = t²` parabola.

https://user-images.githubusercontent.com/69889565/182572742-1bf95a1d-ca99-43cf-abfb-c4ff88744d5f.mp4

## fastLinearToSlowEaseIn: `0.18, 1.0, 0.04, 1.0`

### A curve that is **very steep and linear at the beginning**, but **quickly flattens out** and **very slowly eases in**

By default is the curve used to animate pages on iOS back to their original
position if a swipe gesture is ended midway through a swipe.

https://user-images.githubusercontent.com/69889565/182572989-eaa2b56e-2596-445f-a3ba-7ff2b7e1c35e.mp4

## ease: `0.25, 0.1, 0.25, 1.0`

### A cubic animation curve that **speeds up quickly** and **ends slowly**.

https://user-images.githubusercontent.com/69889565/182573929-32e567eb-0c5a-4410-90ef-c8f44482e9eb.mp4

## easeIn: `0.42, 0.0, 1.0, 1.0`

### A cubic animation curve that **starts slowly** and **ends quickly**.

https://user-images.githubusercontent.com/69889565/182574001-8b5ee96f-f078-44b1-bfe5-ae9850ae34b3.mp4

## easeInToLinear: `0.67, 0.03, 0.65, 0.09`

### A cubic animation curve that **starts slowly** and **ends linearly**.

The symmetric animation to [linearToEaseOut].

https://user-images.githubusercontent.com/69889565/182574058-83334a29-caf8-4e26-bd1e-a9b1982ca9ac.mp4

## easeInSine: `0.47, 0.0, 0.745, 0.715`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This is similar to [Curves.easeIn], but with sinusoidal easing for a slightly less
abrupt beginning and end. Nonetheless, the result is quite gentle and is
hard to distinguish from [Curves.linear] at a glance.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574172-fab861ad-79ab-4ac4-b95b-23412d8f1a07.mp4

## easeInQuad: `0.55, 0.085, 0.68, 0.53`

### A cubic animation curve that **starts slowly** and **ends quickly**.

Based on a quadratic equation where `f(t) = t²`, this is effectively the inverse of
[Curves.decelerate].

Compared to [Curves.easeInSine], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574275-b178d7eb-1e33-4a66-b8cc-37eb4b3a065e.mp4

## easeInCubic: `0.55, 0.055, 0.675, 0.19`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This curve is based on a cubic equation where `f(t) = t³`. The result is a safe sweet
spot when choosing a curve for widgets animating off the viewport.

Compared to [Curves.easeInQuad], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574380-21a0344d-485b-4229-b515-ff9bfe70f9a8.mp4

## easeInQuart: `0.895, 0.03, 0.685, 0.22`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This curve is based on a quartic equation where `f(t) = t⁴`.

Animations using this curve or steeper curves will benefit from a longer
duration to avoid motion feeling unnatural.

Compared to [Curves.easeInCubic], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574513-98822294-ff31-45c5-8999-48116775e99a.mp4

## easeInQuint: `0.755, 0.05, 0.855, 0.06`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This curve is based on a quintic equation where `f(t) = t⁵`.

Compared to [Curves.easeInQuart], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574499-29e964c3-02e0-456c-83e4-29816180244f.mp4

## easeInExpo: `0.95, 0.05, 0.795, 0.035`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This curve is based on an exponential equation where `f(t) = 2¹⁰⁽ᵗ⁻¹⁾`.

Using this curve can give your animations extra flare, but a longer
duration may need to be used to compensate for the steepness of the curve.

Compared to [Curves.easeInQuint], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574904-0392050a-e714-4d58-a948-78e2b22d62ea.mp4

## easeInCirc: `0.6, 0.04, 0.98, 0.335`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This curve is effectively the bottom-right quarter of a circle.

Like [Curves.easeInExpo], this curve is fairly dramatic and will reduce
the clarity of an animation if not given a longer duration.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574863-e5e3bb80-6040-4000-8030-71ecc96d6f18.mp4

## easeInBack: `0.6, -0.28, 0.735, 0.045`

### A cubic animation curve that **starts slowly** and **ends quickly**.

This curve is similar to [Curves.elasticIn] in that it overshoots its bounds before
reaching its end. Instead of repeated swinging motions before ascending,
though, this curve overshoots once, then continues to ascend.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182574833-2cac8b01-d1ce-4ee3-b665-d9ff3f4fbcca.mp4

## easeOut: `0.0, 0.0, 0.58, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

https://user-images.githubusercontent.com/69889565/182574811-b57d22b8-d0f2-4d49-b453-7076372f43db.mp4

## linearToEaseOut: `0.35, 0.91, 0.33, 0.97`

### A cubic animation curve that starts linearly and ends slowly.

A symmetric animation to [easeInToLinear].

https://user-images.githubusercontent.com/69889565/182576349-aad9a4d2-b709-447d-8674-86fa7dd39cf0.mp4

## easeOutSine: `0.39, 0.575, 0.565, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This is similar to [Curves.easeOut], but with sinusoidal easing for a slightly
less abrupt beginning and end. Nonetheless, the result is quite gentle and
is hard to distinguish from [Curves.linear] at a glance.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182576493-e49ac3fc-6077-4c66-8e20-f0456e0a2d7a.mp4

## easeOutQuad: `0.25, 0.46, 0.45, 0.94`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This is effectively the same as [Curves.decelerate], only simulated using a cubic
bezier function.

Compared to [Curves.easeOutSine], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182576573-f792936c-29c9-47a1-96c1-777fdd7dc7af.mp4

## easeOutCubic: `0.215, 0.61, 0.355, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This curve is a flipped version of [Curves.easeInCubic].

The result is a safe sweet spot when choosing a curve for animating a
widget's position entering or already inside the viewport.

Compared to [Curves.easeOutQuad], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182576849-84022ffb-22bb-4073-811a-2c94e42ae659.mp4

## easeOutQuart: `0.165, 0.84, 0.44, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This curve is a flipped version of [Curves.easeInQuart].

Animations using this curve or steeper curves will benefit from a longer
duration to avoid motion feeling unnatural.

Compared to [Curves.easeOutCubic], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182576815-88fe2eab-927a-4581-b8b3-43768eda9e1b.mp4

## easeOutQuint: `0.23, 1.0, 0.32, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This curve is a flipped version of [Curves.easeInQuint].

Compared to [Curves.easeOutQuart], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182576764-54dafb33-d4e9-4f6a-b075-58e0054e0a73.mp4

## easeOutExpo: `0.19, 1.0, 0.22, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This curve is a flipped version of [Curves.easeInExpo]. Using this curve can give your
animations extra flare, but a longer duration may need to be used to
compensate for the steepness of the curve.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577224-2286c837-d199-4fe9-97e3-36474fa97fcd.mp4

## easeOutCirc: `0.075, 0.82, 0.165, 1.0`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This curve is effectively the top-left quarter of a circle.

Like [Curves.easeOutExpo], this curve is fairly dramatic and will reduce
the clarity of an animation if not given a longer duration.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577181-02f19f0b-7d99-41f8-80d9-abe42edec67a.mp4

## easeOutBack: `0.175, 0.885, 0.32, 1.275`

### A cubic animation curve that **starts quickly** and **ends slowly**.

This curve is similar to [Curves.elasticOut] in that it overshoots its bounds before
reaching its end. Instead of repeated swinging motions after ascending,
though, this curve only overshoots once.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577164-d499f59e-1b02-4e9b-b6b3-d6295dcbf902.mp4

## easeInOut: `0.42, 0.0, 0.58, 1.0`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

https://user-images.githubusercontent.com/69889565/182577139-f5b39992-1be3-4660-b085-33d2a70a4364.mp4

## easeInOutSine: `0.445, 0.05, 0.55, 0.95`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

This is similar to [Curves.easeInOut], but with **sinusoidal easing** for a slightly less abrupt beginning and end.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577754-6e4ae182-14cf-4e53-99da-341b620ece8c.mp4

## easeInOutQuad: `0.455, 0.03, 0.515, 0.955`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

This curve can be imagined as [Curves.easeInQuad] as the first half, and [Curves.easeOutQuad] as the second.

Compared to [Curves.easeInOutSine], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577805-24b0c54c-777e-4154-a1c5-8a9c4aa38a8c.mp4

## easeInOutCubic: `0.645, 0.045, 0.355, 1.0`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

This curve can be imagined as [Curves.easeInCubic] as the first half, and [Curves.easeOutCubic] as the second.

The result is a safe sweet spot when choosing a curve for a widget whose
initial and final positions are both within the viewport.

Compared to [Curves.easeInOutQuad], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577830-5afed587-bb51-48a4-8015-e86dc116e693.mp4

## easeInOutQuint: `0.86, 0.0, 0.07, 1.0`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

This curve can be imagined as [Curves.easeInQuint] as the first half, and [Curves.easeOutQuint] as the second.

Compared to [Curves.easeInOutQuart], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577854-14b852c8-0ca3-41a7-bff1-6a2b8d31c0d9.mp4

## easeInOutExpo: `1.0, 0.0, 0.0, 1.0`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

Since this curve is arrived at with an exponential function, the midpoint is exceptionally steep.

Extra consideration should be taken when designing
an animation using this.

Compared to [Curves.easeInOutQuint], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577920-acb092e7-725f-4f1a-9cd7-c12dabbb7ae2.mp4

## easeInOutCirc: `0.785, 0.135, 0.15, 0.86`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

This curve can be imagined as [Curves.easeInCirc] as the first half, and [Curves.easeOutCirc] as the second.

Like [Curves.easeInOutExpo], this curve is fairly dramatic and will reduce
the clarity of an animation if not given a longer duration.

Compared to [Curves.easeInOutExpo], this curve is slightly steeper.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182577990-b856d208-8358-43fb-8f3f-6d88d199e3ea.mp4

## easeInOutBack: `0.68, -0.55, 0.265, 1.55`

### A cubic animation curve that **starts slowly**, **speeds up**, and then **ends slowly**.

This curve can be imagined as [Curves.easeInBack] as the first half, and [Curves.easeOutBack] as the second.

Since two curves are used as a basis for this curve, the resulting
animation will overshoot its bounds twice before reaching its end - first
by exceeding its lower bound, then exceeding its upper bound and finally descending to its final position.

Derived from Robert Penner’s easing functions.

https://user-images.githubusercontent.com/69889565/182578136-8271afdb-df08-4321-8a74-d15cf59a831e.mp4

## SlowInFastOut `0.4, 0.0, 0.2, 1.0`

### A curve that **starts quickly** and **eases into its final position**.

Over the course of the animation, the object spends more time near its
final destination. As a result, the user isn’t left waiting for the
animation to finish, and the negative effects of motion are minimized.

https://user-images.githubusercontent.com/69889565/182578396-606e55c3-dab9-4890-9db3-46d501022969.mp4

**standardEasing**, the name for this curve in the Material specification.

## FastInSlowMiddle `0.15, 0.85, 0.85, 0.15`

### A cubic animation curve that **starts quickly**, **slows down**, and then **ends quickly**.

https://user-images.githubusercontent.com/69889565/182578292-9975718e-eb60-484a-947d-49195e368b47.mp4

## BounceIN

### An oscillating curve that grows in magnitude.

https://user-images.githubusercontent.com/69889565/182565127-79148519-a10d-48dc-87e8-46a16bb22039.mp4

## BounceOut

### An oscillating curve that first grows and then shrink in magnitude.

https://user-images.githubusercontent.com/69889565/182566512-592d4957-3939-49dc-9c6e-e2415709cb1b.mp4

## BounceInOut

### An oscillating curve that first grows and then shrink in magnitude.

https://user-images.githubusercontent.com/69889565/182566918-79c2ef4f-4c7c-40f6-b4be-8ef6b5ab8aee.mp4

## ElasticIn

### An oscillating curve that grows in magnitude while overshooting its bounds.

https://user-images.githubusercontent.com/69889565/182578589-e12bc222-ce0b-4ce0-b304-b9128f837bba.mp4

## ElasticOut

### An oscillating curve that shrinks in magnitude while overshooting its bounds.

https://user-images.githubusercontent.com/69889565/182578557-94ec7243-f649-4322-895c-3bd7ffd131c7.mp4

## ElasticInOut

### An oscillating curve that grows and then shrinks in magnitude while overshooting its bounds.

https://user-images.githubusercontent.com/69889565/182578581-16aab7a5-bafd-4b91-a593-397801e8f2be.mp4
