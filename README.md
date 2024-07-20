# Can you hold on during tornado?
## A GPU-accelerated fluid dynamics simulator using Neural Operators


### About
You'd think that this is a engineering product but actually this is a personal training app.

By modeling fluid dynamics in different situations during tornado we estimate the force of grip you'd need to have, given your body's complections, to hold on and not get sucked in. Then, we collect your current stats in the gym (how much u bench press, how much u curl, situp and etc.) and 1) show if u can can hold on in different situations (under the bride, on the parking lot, by holding someones hand, by holding on to a flag pole) during T1-T5 tornado, 2) give u a training plan to achieve muscular tone u'd need to do it.

#### Ultimately, we want to answer the question: Could you manage to hold on to Daisy E. Jones under the overpass in scene from the movie "Twisters" during a F5 tornado.

### Roadmap:
- [ ] measure force on a round ball on a flat surface with unidirectional wind
- [ ] measure force on a avg. human on a flat surface with unidirectional wind
- [ ] model the overpass scene from the movie "Twisters"

### Additional roadmap:
- [ ] run classical physics simulator methods on CPU
- [ ] run Neural Operators (NOs) on GPU and measure speedup
- [ ] make nice visualisations
