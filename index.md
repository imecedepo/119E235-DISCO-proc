## DISCO-Proc: DIstributed Storage, near-optimal COding and Protocol design for data caching through device to device communications in cooperative cellular networks.

In cellular networks, with the popular files being cached, the interaction between devices significantly reduces the
communication load on the base station (BS). The caching can be accomplished by distributing the partitions of a popular
file to mobile devices either in an uncoded or coded form using erasure coding. Any piece of the chunked content can either be retrieved from the neighboring mobile devices or, if not possible, from the BS directly, at the expense of a higher
communication cost. Considering a cellular network, in which a cell contains a set of nodes, some of which are arriving
and some are departing at random times, intelligent data repair methods will be needed to ensure a minimum level of
communication with the base station (BS). Involvement of a BS or more than one BS adds another dimension to previous
repair paradigms, especially to the cooperative repair process due to the changes in the set of constraints and
operating protocol rules. There is no work which studies the bandwidth/storage trade-off for this particular case.
Accordingly, novel cell architectures will call for different design considerations including but not limited to novel code
constructions, protocol designs, data access latency, realistic queuing models and simulation platforms. In this
project, unlike the previous research, we initially aim to obtain improved theoretical bounds for the bandwidth and
storage capacity using data flow diagrams while BSs are cooperatively helping to repair the lost data. In addition,
inspired by the code structures that utilize bandwidth and storage space efficiently, completely genuine graph-based
code constructions as well as novel repair algorithms on these codes will be proposed to achieve near-optimality. Novel
approaches such as genetic algorithm and optimal left-over data distributions shall be proposed that have not
previously been applied to the node repair problem in literature. Besides that, highly novel protocol designs based on
energy efficiency for check-in and check-out processes, will be proposed, which will help minimize the bandwidth and data
storage requirements. These protocols will be strengthened by transition (hand-off) scenarios, which will allow nodes to
migrate from one cell to another, while enabling the BSs to collaborate and help effectively use the intracellular resources.
This involves few novelties such as adjusting repair intervals (thresholds), reducing data access overheads, the use
of incoming node contents, intelligent left-over data handling etc. Finally, various known and more realistic queuing
models will be used to analytically evaluate the proposed code structures and the performance of the protocol
architecture. In order to verify our analytical results, large scale cellular network simulations will be performed in order to
numerically derive overall communication and file maintenance cost as well as comparisons.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/imecedepo/119E235-DISCO-proc/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
