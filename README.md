# LLMs-Accelearation
Large Language Models' Paper List
### **7. Efficiency**

**Communication-Based:**  Improving efficiency by reducing model parameters transmission.

**Hardware-Based:**  Improving efficiency by hardware acceleration (GPU, FPGA, etc.)

**Algorithm-Based:**   Improving efficiency by accelerating model convergence rate (local training, model aggregation, client selection, etc.)

<table border=0 cellpadding=0 cellspacing=0 >
	<col width="10%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="20%" style='mso-width-source:userset;mso-width-alt:10944'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="10%" align="center">Taxonomy</td>
		<td class=xl6519452 width="65%" align="center">Papers</td>
		<td class=xl6519452 width="20%" align="center">Techniques</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=8 height=152 class=xl6519452 style='height:85.5pt' align="center">Communication-Based</td>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1909.07588.pdf">Communication-Efficient Distributed Learning via Lazily Aggregated Quantized Gradients</a></td>
        <td class=xl6519452 align="center"><font size="2">Quantization</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://ieeexplore.ieee.org/document/9238427">Lazily Aggregated Quantized Gradient Innovation for Communication-Efficient Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Quantization</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2104.06023.pdf">Communication Efficient Federated Learning with Adaptive Quantization</a></td>
        <td class=xl6519452 align="center"><font size="2">Quantization</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1610.02132.pdf">QSGD: Communication-Efficient SGD via Gradient Quantization and Encoding</a></td>
        <td class=xl6519452 align="center"><font size="2">Quantization</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2204.02321.pdf">SAFARI: Sparsity enabled Federated Learning with Limited and Unreliable Communications</a></td>
        <td class=xl6519452 align="center"><font size="2">Sparsity</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2001.08600.pdf">RPN: A Residual Pooling Network for Efficient Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Sparsity</font></td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/1910.03581.pdf">FedMD: Heterogenous Federated Learning via Model Distillation</a></td>
        <td class=xl6519452 align="center"><font size="2">Knowledge Distillation</font></td>
		<td class=xl6519452 align="center"><a href="https://github.com/diogenes0319/FedMD_clean">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2006.07242.pdf">Ensemble distillation for robust model fusion in federated learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Knowledge Distillation</font></td>
		<td class=xl6519452 align="center"><a href="hhttps://github.com/epfml/federated-learning-public-code">code</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=3 height=57 class=xl6519452 style='height:85.5pt' align="center">Hardware-Based</td>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.10560.pdf">FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">FPGA-Based Acceleration</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://dmle.iais.fraunhofer.de/papers/muecke2019hardware.pdf">Hardware Accelerated Learning at the Edge</a></td>
        <td class=xl6519452 align="center"><font size="2">GPU-Based Acceleration</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2107.13797.pdf">HAFLO: GPU-Based Acceleration for Federated Logistic Regression</a></td>
        <td class=xl6519452 align="center"><font size="2">GPU-Based Acceleration</font></td>
        <td class=xl6519452 align="center"></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:14.25pt'></td>
    	<td class=xl6519452></td>
    	<td class=xl6519452></td>
        <td class=xl6519452></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td rowspan=5 height=95 class=xl6519452 style='height:85.5pt' align="center">Algorithm</td>
    	<td class=xl6519452 style='height:14.25pt' align="center"><a href="https://arxiv.org/pdf/2007.07682.pdf">FetchSGD: Communication-Efficient Federated Learning with Sketching</a></td>
        <td class=xl6519452 align="center"><font size="2">Optimization</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928454/fetchsgd-communicationefficient-federated-learning-with-sketching">Video</a><br><a href="https://github.com/kiddyboots216/CommEfficient">Code</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
		<td height=19 class=xl6619452 width=815 style='height:14.25pt;width:611pt' align="center"><a href="https://arxiv.org/abs/2002.11364">Acceleration for Compressed Gradient Descent in Distributed and Federated Optimization</a></td>
        <td class=xl6519452 align="center"><font size="2">Optimization</font></td>
        <td class=xl6519452 align="center"><a href="https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-15-19-00UTC-6191-acceleration_fo.pdf">Slide</a><br><a href="https://slideslive.com/38927921/acceleration-for-compressed-gradient-descent-in-distributed-optimization">Video</a></td>
    </tr>
	<tr height=19 style='height:14.25pt'>
    	<td class=xl6619452 width=815 style='width:611pt' align="center"><a href="http://proceedings.mlr.press/v119/hamer20a/hamer20a.pdf">FedBoost: A Communication-Efficient Algorithm for Federated Learning</a></td>
        <td class=xl6519452 align="center"><font size="2">Optimization</font></td>
        <td class=xl6519452 align="center"><a href="https://slideslive.com/38928463/fedboost-a-communicationefficient-algorithm-for-federated-learning?ref=speaker-16993-latest">Video</a></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://arxiv.org/pdf/1610.05492.pdf">Federated Learning: Strategies for Improving Communication Efficiency</a></td>
		<td class=xl6519452 align="center"><font size="2">Optimization</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.25pt'>
    	<td height=19 class=xl6519452 style='height:85.5pt' align="center"><a href="https://arxiv.org/pdf/1902.11175.pdf">One-Shot Federated Learning</a></td>
		<td class=xl6519452 align="center"><font size="2">Model Aggregation</font></td>
        <td class=xl6519452 align="center"></td>
	</tr>
</table>

&nbsp; 