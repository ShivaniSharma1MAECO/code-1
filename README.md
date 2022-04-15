# code-1

ggplot(data = dat_small,
       mapping = aes(x = WEALTH, y = science)) +
  geom_point(aes(color = sex)) +
  facet_wrap( ~ Region) +
  labs(x = "Family Wealth", y = "Science Scores") +
  theme_bw() +
  theme(legend.title = element_blank())
