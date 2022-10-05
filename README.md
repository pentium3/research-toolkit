# research-toolkit

reusable code/guidelines for research

## plot figures

matplotlib

gnuplot

## python scripts

run cmdline

## latex

add figures to latex

Special characters

## paper writing

#### How to describe an experiment/plot?

1. Where. 
    - "In FigureX / In the table on Page3, we show that ..."
2. Why. 
    - "We are running exp to see how much overhead does tracing have / show that SysX is faster / ..."
3. What. The experiment setup. anything that could help the reader to reproduce the exp. 
    - "We run xxx on yyy system and measure the CDF of latency for every requests. "
4. Describe plot. 
    - "We see that as parallelism increases, the latency dropped by xx%. XXX has highest latency."
5. Highlights. What we want the readers to notice.
    - "When parallelism==4, we found that ...sth interesting..."
6. Implifications/Conclusions. 
    - "The SysX has xx% lower latency. The SysX system achieves better performance while using less resources."



