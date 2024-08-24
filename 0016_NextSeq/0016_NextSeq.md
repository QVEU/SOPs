|SOP #WEO-0016             |<p>v1.0</p><p>Orr, Walker (NIH/NIAID) [F]</p><p>11/1/23 2:08:00 PM</p>|
| :- | -: |

***Launching Illumina NextSeq 2000***

*Walker Orr, 11/01/2023*


## **Thawing the Reagent Cartridge**

|<p>Option 1: Thawing in a water bath.</p><p>1. Take the reagent cartridge out of the box but ***leave it in the foil bag***.</p><p>2. Prepare a 25C water bath to a depth of 9.5-10 cm.</p><p>3. Place the reagent cartridge in the water bath (it will float) for 6-8 hours (do ***not*** exceed 8 hours).</p><p>4. Remove the cartridge from the water bath and pat dry with paper towels.</p>|
| :- |
|<p>Option 2: Thawing in the refrigerator.</p><p>1. One day prior to your sequencing run, take the reagent cartridge out of the box but ***leave it in the foil bag.***</p><p>2. Place the cartridge on the bench with the label face up so air can circulate on all sides.</p><p>3. Leave the reagent cartridge on the bench for 6 hours.</p><p>4. Place the cartridge in a 2-8C refrigerator with the label face up so air can circulate on all sides.</p><p>5. Leave the reagent cartridge in the refrigerator for 12-72 hours (do ***not*** exceed 72 hours).</p>|
|<p>Option 3: Thawing on the bench</p><p>1. One day prior to your sequencing run, take the reagent cartridge out of the box but ***leave it in the foil bag.***</p><p>2. Place the cartridge on the bench with the label face up so air can circulate on all sides.</p><p>3. Leave the cartridge on the bench for 9-16 hours (do ***not*** exceed 16 hours).</p>|
\*

## **Preparing a Samplesheet**

|1. Go to Basespace (basespace.illumina.com).|
| :- |
|2. Go to runs. On the runs page, click new run > run planning.|
|3. On the first screen (“run settings”, select NextSeq 1000/2000 as the instrument. For secondary analysis, choose **local**.|
|4. Under “configuration,” choose “Illumina DRAGEN BCL Convert – 3.8.4.” For “library prep kit” and “index adapter kit,” choose “not specified” (at the very bottom of the dropdowns).|
|5. You will now be asked for more information (“Configuration: Illumina DRAGEN BCL Convert - 3.8.4”).|
|6. Enter the index reads length (10 for Twist UDI plate) and the read length (150 for 300 cycles, 250 for 500 cycles, etc). |
|7. Enter your sample name and the adapter sequences. You can also bulk import these using a template spreadsheet.|
|8. Under the “Analysis Setting” heading, enter the sequences for the Twist Universal Adapters. These are: |

|AGATCGGAAGAGCACACGTCTGAACTCCAGTCA|
| :- |
|AGATCGGAAGAGCGTCGTGTAGGGAAAGAGTGT|

|For read1 and read2, respectively. Allow one barcode mismatch for each read. Under “FASTQ Compression Format” choose **gzip**.|
| :- |
|9. You will be prompted to a preview screen. Choose “export” to generate your sample sheet. **DO NOT CHANGE YOUR SAMPLESHEET NAME**, as this can create problems for the sequencer.|
##
## **Final Library Preparation and Run Initiation**

|<p>**Quantitation and Preliminary Pooling**</p><p>1. Quantitate each library using Qubit and obtain the size using TapeStation D1000.</p><p>2. Convert to nanomolar concentration using the illumina website, or this formula:</p><p>&emsp;concentration in ng/ulaverage library size in bp\*106660gmol=concentration in nM</p><p>3. Thaw Illumina’s RSB/Tween for use in the pool.</p><p>4. Dilute libraries to 10 nM in nuclease-free water.</p><p>5. Dilute libraries to 2 nM each in RSB/Tween in a DNA LoBind tube. This will be 2 ul of 10 nM library in 8 ul of RSB/Tween. You will need a total of 25 ul library.</p><p>6. Double-check concentration with Qubit HS if desired.</p>|
| :- |
|<p>**Final Dilution and PhiX Spike-In**</p><p>1. Allow flow cell and reagent cartridge to come to room temperature (15 minutes to 1 hour). You will also need the 2 nM pool, 1 nM PhiX (-20C) and more RSB/Tween.</p><p>2. Prepare a final dilution (650 pm) of pooled libraries by mixing 7.8 ul 2 nM library pool with 16.2 ul of RSB/Tween.</p><p>3. Pool 1 ul 1 nM PhiX with 24 ul 2 nM library for a total of 25 ul (~2% PhiX spike-in). Vortex final pool briefly, spin down, and set aside on ice.</p><p>&emsp;a. If using stock 10 nM PhiX: Prepare 20 ul 1 nM PhiX by combining 1 ul 10 nM PhiX with 9 ul RSB/Tween (always prepare fresh).</p>|
|<p>**Loading Cartridge and Starting the Run**</p><p>1. Open the cartridge bag and remove carefully.</p><p>2. Invert cartridge 10 times to mix reagents (side-to-side).</p><p>3. Open flow cell package carefully. Mount the flow cell in the cartridge. Hold the flow cell by the grey tab to expose the flow cell.</p><p>4. Using a new P1000 pipette tip, pierce the library reservoir and push the goil to the edges to enlarge the hole. Discard the tip.</p><p>5. Add 20 ul diluted of final pool to the bottom of the reservoir by slowly lowering the pipette tip to the bottom of the reservoir before dispensing.</p><p>&emsp;a. Avoid touching the foil.</p><p>&emsp;b. You will not be able to see the bottom of the well, so you have to feel it.</p><p>6. Bring the loaded cartridge to the sequencer.</p><p>7. Press “Start” and follow the prompts. </p><p>&emsp;a. Make sure to choose “external folder” (i.e., the hard drive) for the output folder location.</p><p>8. You will load the machine with the flow cell pointing internal to the machine. The 600 cycles kits cartridge will stick out a bit from the sequencer, as this cartridge holds more reagents.</p><p>9. Wait for the sequencer to do its warm-up routine. This takes around 20 minutes for all the checks.</p>|

1

