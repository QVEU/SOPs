|SOP #WEO-0006-A                      |<p>v1.0</p><p>Orr, Walker (NIH/NIAID) [F]</p><p>3/27/23 2:26:00 PM</p>|
| :- | -: |

**KAPA HiFi HotStart PCR**

*Walker Orr, 03/27/2023*

**Application**

Amplifying oligo pools and other short <1 kbp amplicons, with high fidelity.

**Required Equipment**

PCR Block

**Required Reagents**

Kit reagents for KAPA HiFi HotStart PCR:

- 5x High Fidelity or GC Buffer: 5 µL/sample
- 10 mM KAPA dNTP mix: 0.75 µL/sample
- Template DNA and appropriate forward and reverse primers
- KAPA HiFi HotStart DNA Polymerase: 0.5 µL/reaction

**Sample Workflow**

Total time: Variable

Active time: 15 minutes

**General Comments**
**


1. Prepare PCR master mix. The reaction MUST be set up on ice!! Thaw, vortex, and spin buffers; thaw and flick or pipette primers. Master mix will contain all reaction components common to all PCR reactions. See “Reaction Volumes,” below.
1. Transfer the appropriate volumes of PCR master mix, template, and primers to individual PCR tubes or wells. Mix well (multichannel pipette is helpful) and spin down.
1. Perform the PCR; see “Reaction Conditions,” below.

**Reaction Volumes**

|**Component**|**[Final]**|**25 µL reaction**|
| :- | :- | :- |
|Nuclease-free water||To 25 µL|
|5x KAPA HiFi Buffer (Fidelity ![ref1] or GC ![ref2])|1x|5\.0 µL|
|10 mM KAPA dNTP mix ![ref3]|.3 mM each|0\.75 µL|
|10 µM Forward primer|.3 µM|0\.75 µL|
|10 µM Reverse primer|.3 µM|0\.75 µL|
|Template DNA|As required|As required|
|1 U/µL KAPA HiFi HotStart DNA Polymerase ![ref4]|0\.5 U|0\.5 µL|

Considerations:

1. ****Reaction volumes may be adjusted between 10-50 µL. For volumes other than 25 µL, scale reagents proportionately. Reaction volumes >50 µL are not recommended.
1. KAPA HiFi Buffers contain 2 mM MgCl<sub>2</sub> (1x). Additional MgCl<sub>2</sub> may be added separately. Use the GC Buffer only if the Fidelity Buffer gives poor results.
1. Use <100 ng genomic DNA (10-100 ng) and <1 ng less complex DNA (0.1-1 ng) per 25 µL reaction as a first approach.

**Reaction Conditions**

<table><tr><th valign="top"><b>Step</b></th><th valign="top"><b>Cycles</b></th><th valign="top"><b>Temperature</b></th><th valign="top"><b>Duration</b></th></tr>
<tr><td valign="top">Initial denaturation</td><td valign="top">1</td><td valign="top">95°C</td><td valign="top">3 minutes</td></tr>
<tr><td valign="top">Denaturation</td><td rowspan="3">15-35</td><td valign="top">98°C</td><td valign="top">20 seconds</td></tr>
<tr><td valign="top">Annealing</td><td valign="top">60-75°C</td><td valign="top">15 seconds</td></tr>
<tr><td valign="top">Extension</td><td valign="top">72°C</td><td valign="top">15-60 seconds/kb</td></tr>
<tr><td valign="top">Final extension</td><td valign="top">1</td><td valign="top">72°C</td><td valign="top">1 min/kb</td></tr>
</table>

Considerations:

1. ****Initial denaturation for 3 minutes at 95°C is sufficient for most applications. Use 5 min. at 95°C for GC-rich targets (>70% GC content).
1. The optimal annealing temperature for a specific primer set is likely to be different (higher) than when used in a conventional PCR buffer. An annealing temperature gradient PCR is recommended to determine the optimal annealing temperature with KAPA HiFi HotStart. If gradient PCR is not feasible, anneal at 65°C as a first approach.
1. Two-step cycling protocols with combined annealing/extension temperature in the range of 68-75°C and a combined annealing/extension time of 30 seconds/kb may be used.
1. Use 15 second extension per cycle for targets ≤1 kb, and 30-60 seconds/kb for longer fragments, or to improve yields.
1. For highest fidelity, use ≤25 cycles. In cases where very low template concentrations or low reaction efficiency results in low yields, 30-35 cycles may be performed to produce sufficient product for downstream applications.

**Reaction Calculator**

|**Reaction Volumes**|**[Final]**|**25 µL rxn (µL)**|**Master Mix (µL)**|**√**|
| :- | :- | :- | :- | :- |
||**# of samples:**|<a name="text2"></a>|||
|Nuclease-free water||16.25|0.00||
|5x KAPA HiFi Buffer (Fidelity ![ref1] or GC ![ref2])||5\.00|0.00||
|10 mM KAPA dNTP mix ![ref3]||0\.75|0.00||
|10 µM Forward primer|<a name="box1"></a>|0\.75|0.00|0<a name="check1"></a>1|
|10 µM Reverse primer|<a name="box2"></a> |0\.75|0.00|0|
|Template DNA|<a name="box3"></a> |<a name="text3"></a>|0.00|0|
|1 U/µL KAPA HiFi HotStart DNA Polymerase ![ref4]||0\.5|0.00||
|**Totals**||25.00|0.00||

<table><tr><th valign="top"><b>Cycles</b></th><th valign="top"><b>Step</b></th><th valign="top"><b>Temperature</b></th><th valign="top"><b>Duration</b></th></tr>
<tr><td valign="top">1</td><td valign="top">Initial denaturation</td><td valign="top">95°C</td><td valign="top"><a name="dropdown1"></a></td></tr>
<tr><td rowspan="3"><a name="cycles"></a></td><td valign="top">Denaturing</td><td valign="top">98°C</td><td valign="top">20 seconds</td></tr>
<tr><td valign="top">Annealing</td><td valign="top"></td><td valign="top">15 seconds</td></tr>
<tr><td valign="top">Extension</td><td valign="top">72°C</td><td valign="top">15-60 sec/kb</td></tr>
<tr><td valign="top">1</td><td valign="top">Final Extension</td><td valign="top">72°C</td><td valign="top">1 min./kb</td></tr>
</table>

1

[ref1]: Aspose.Words.6d8462e9-5714-4254-af23-ce6d3f642881.001.png
[ref2]: Aspose.Words.6d8462e9-5714-4254-af23-ce6d3f642881.002.png
[ref3]: Aspose.Words.6d8462e9-5714-4254-af23-ce6d3f642881.003.png
[ref4]: Aspose.Words.6d8462e9-5714-4254-af23-ce6d3f642881.004.png
