---
title: "Instructor Notes"
---

Vi springer geom_col over - for den forudsætter at vi 
selv foretager en optælling. Og selvom group_by i
kombination med summarise forudsættes bekendt, ligger den
langt væk.

Ellers er eksemplet:
diamonds %>% 
  group_by(color) %>% 
  summarise(count = n()) %>% 
  ggplot(aes(x=count)) +
    geom_col()

{% include links.md %}
