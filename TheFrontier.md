# Part 3b: The energy frontier (optional but with one relevant calculation)

## Experimental Searches for new phenomena

Part 3b of the course gives examples of recent ATLAS searches to find new phenomena at the high energy frontier. These examples cover resonant production as well as the scattering deviating from the prediction at high energies. In either case, the result of these searches is a limit on a specific new particle or phenomena that is tested in the measurements.

```{admonition} Calculation

<b>Upper Limit on the cross-section</b>

Most particle physics measurements ultimately are based on the observed number of events with a specific property (e.g. $\alpha$ particles scattered at an angle of 100$\degree$), that is they measure $N \pm \Delta N$. Here $\Delta N$ is the uncertainty on the number of observed particles coming both from statistical fluctuations in the measurement (for counting experiments this is usually approximated as $\sqrt{N}$) and the systematic uncertainty (coming from uncertainties in the detector sensitivity).

For any measurement, the number of signal events $N^{\textrm{signal}}$ (i.e. those of a hypothesized particle we want to observe or those that would be an excess over the expectation) can be calculated as $N^{\textrm{signal}} = N^{\textrm{observed}} - N^{\textrm{background}}$ with $N^{\textrm{observed}}$ being all observed events and $N^{\textrm{background}}$ being the number of events that are predicted by the Standard Model. If there is no new physics signal, then $N^{\textrm{observed}} = N^{\textrm{background}}$ and $N^{\textrm{signal}} = 0$.

However, we still have an uncertainty $\Delta N$ that comes from the background. A downwards fluctuation in the background, could be compensated by the signal, but we cannot know that this is the case. In other words, let's assume, we observed 100 events and expect 100 ($\pm 10$) background events from the Standard Model prediction. Therefore, we have 0 estimated signal events. However our uncertainty even in the best case will be 10 event (from the statistical fluctuation of the 100 background events). We **cannot** know, if the 100 events that we observe are: 100 background events or 90 background events (i.e. we have a statistical fluctuations downwards) and 10 signal events.

We can then turn our observations into a limit on the cross-section based on the maximum number of particles, that could be obscured by the uncertainty on our measurement, e.g. because there is a downwards fluctuation on the number of Standard Model events.

We use the known cross-section formula using and solve it for $\sigma$
$$
\sigma = N / L
$$

As $\Delta N$ is the maximum number of particles that could be hidden in the data, this means, $\sigma$ is the maximum cross-section for a phenomena to occur, that we could still have missed given our data. This gives us a limit on the cross-section to produce a new particle $X$. Using a Luminosity of 140 fb$^{-1}$ (the amount of data taken by ATLAS in the years 2015-2018), we will get:

$$
\sigma_X = 10 / (120~\textrm{fb}^{-1} ) = 0.083~\textrm{fb}
$$

If we have a theory that would require particle $X$ to be produced with a cross-section of 10 fb to explain Dark Matter, we could exclude it.

```

%## Resonances: Production of a particle


%## Scattering: Deviations in the high energy tails


