# full-screen-navigation

Creating a simple navigation with the implementation of gsap for JavaScript animation.

## Notice

Mobile-responsive is not supported at the moment.

## Getting Started

### Dependencies

- gsap

### Implementing

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.7.0/gsap.min.js" integrity="sha512-2fk3Q4NXPYAqIha0glLZ2nluueK43aNoxvijPf53+DgL7UW9mkN+uXc1aEmnZdkkZVvtJZltpRt+JqTWc3TS3Q==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

### Timeline

- A Timeline is a powerful sequencing tool that acts as a container for tweens and other timelines, making it simple to control them as a whole and precisely manage their timing. Without Timelines, building complex sequences would be far more cumbersome because you'd need to use a delay for every animation

### Example

```
// WITHOUT Timelines (only using tweens with delays):
gsap.to("#id", {x: 100, duration: 1});
gsap.to("#id", {y: 50, duration: 1, delay: 1});      //wait 1 second
gsap.to("#id", {opacity: 0, duration: 1, delay: 2}); //wait 2 seconds

// then we can control the whole thing easily...
tl.pause();
tl.resume();
tl.seek(1.5);
tl.reverse();
```

### Documentation

Link: https://greensock.com
