## LLMs Acceleration Paper List
This list of papers is categorized by technology. 

A list categorized by conference will be added in the future.
<table border=0 cellpadding=0 cellspacing=0 >
	<col width="10%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="20%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="10%" align="center">Methodology</td>
		<td class=xl6519452 width="65%" align="center">Papers</td>
		<td class=xl6519452 width="20%" align="center">Publication Venue/Affiliations</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=9 height=14.25 class=xl6519452 style='height:99.75pt' align="center">Quantization</td>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://proceedings.neurips.cc/paper_files/paper/2019/hash/36ab62655fa81ce8735ce7cfdaf7c9e8-Abstract.html">SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight Compression</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/Vahe1994/SpQR">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2306.00978">AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/mit-han-lab/llm-awq">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2210.17323">GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers</a></td>
        <td class=xl6519452 align="center"><font size="2">ICLR 2023</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/IST-DASLab/gptq">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2306.02272">OWQ: Lessons learned from activation outliers for weight quantization in large language models</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/xvyaward/owq">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2206.09557">LUT-GEMM: Quantized Matrix Multiplication based on LUTs for Efficient Inference in Large-Scale Generative Language Models</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2022</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/adf7fa39d65e2983d724ff7da57f00ac-Abstract-Conference.html">Zeroquant: Efficient and affordable post-training quantization for large-scale transformers</a></td>
        <td class=xl6519452 align="center"><font size="2">NeurIPS 2022</font></td>
	<td class=xl6519452 align="center"><a href="https://github.com/microsoft/DeepSpeed">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://proceedings.mlr.press/v202/xiao23c.html">SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/mit-han-lab/smoothquant">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2304.01089">RPTQ: Reorder-based Post-training Quantization for Large Language Models</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/hahnyuan/RPTQ4LLM">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2304.01089">Outlier Suppression+: Accurate quantization of large language models by equivalent and optimal shifting and scaling</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
		<td class=xl6519452 align="center"></a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=5 height=57 class=xl6519452 style='height:85.5pt' align="center">Sparsity</td>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2310.06694.pdf">Sheared LLaMA: Accelerating Language Model Pre-training via Structured Pruning</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
        	<td class=xl6519452 align="center"><a href="https://github.com/princeton-nlp/LLM-Shearing">code</a></td>
    </tr>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2306.11695">A Simple and Effective Pruning Approach for Large Language Models</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
        	<td class=xl6519452 align="center"><a href="https://github.com/locuslab/wanda">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2305.11627">LLM-Pruner: On the Structural Pruning of Large Language Models</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/horseee/LLM-Pruner">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://proceedings.mlr.press/v202/liu23am.html">Deja Vu: Contextual Sparsity for Efficient LLMs at Inference Time</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/FMInference/DejaVu">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2301.00774">SparseGPT: Massive Language Models Can be Accurately Pruned in One-Shot</a></td>
        <td class=xl6519452 align="center"><font size="2">ICML 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/IST-DASLab/sparsegpt">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=2 height=95 class=xl6519452 style='height:85.5pt' align="center">Attention Pattern</td>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/abs/2309.17453">Efficient Streaming Language Models with Attention Sinks</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
        <td class=xl6519452 align="center"><a href="https://github.com/mit-han-lab/streaming-llm">code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2309.12307.pdf">LongLORA: Efficient Fine-tuning of Long Context Large Language Model</a></td>
        <td class=xl6519452 align="center"><font size="2">Arxiv 2023</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/dvlab-research/LongLoRA">code</a></td>
    </tr>
</table>
