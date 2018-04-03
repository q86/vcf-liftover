# vcf-liftover: A tool to convert VCF genome coordinates using liftOver.

The tool reads VCF from stdin and outputs to stdout.

## Usage:
Enter ``./vcf-liftover`` will print the usage:

```shell
Usage: zcat test.vcf.gz | vcf-liftover chainfile [unmappedfile]
```

Here is an example:
```shell
 zcat test.vcf.gz | ./vcf-liftover GRCh37_to_GRCh38.chain.gz
```
