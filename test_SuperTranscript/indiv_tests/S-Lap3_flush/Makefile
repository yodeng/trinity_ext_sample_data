
test:
	../../../../Analysis/SuperTranscripts/Trinity_gene_splice_modeler.py --trinity_fasta S-Lap3.flush.fa --no_squeeze --no_refinement --out_prefix st --debug
	diff st.gtf st.gtf.expected_result

clean:
	rm -f ./st.fa ./st.gtf


