# M2Convertor
Convert Standard M2 format to parallel sentences.
For M2 format and its usage details, please see https://github.com/chrisjbryant/errant for more information.

## Usage
python conv_m2.py -f <m2_file> -p <output_prefix>

## Outputs
`*.src`: file of source sentences
`*.trg`: file of target sentences, only editor 0's annotation is contained.
`*.para`: file which contains parallel sentences.
> For *.para, lines begining with "S " refers to source sentences, while "T0" refers to target sentences annotated by editor 0, as the number next to "T" indicates the editor number in the input m2 file.
