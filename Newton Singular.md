
$$
\begin{array}{rl}
Q(X+tH)^{T}Q(X+tH) &= t^{4}(H^{2T}A^{T}AH^{2}) \\
	&+ t^{3}(H^{2T}A^{T}AXH + H^{T}X^{T}A^{T}AH^{2} + H^{2T}A^{T}AHX + X^{T}H^{T}A^{T}AH^{2} \\
	&+ H^{2T}A^{T}BH + H^{T}B^{T}AH^{2}) \\
	&\\
	&+ t^{2}(X^{2T}A^{T}AH^{2} + H^{2T}A^{T}AX^{2} + X^{T}B^{T}AH^{2} + H^{2T}A^{T}BX \\
    &+ C^{T}AH^{2} + H^{2T}A^{T}C + (AHX+AHX+BH)^{T}(AHX+AHX+BH))\\
    &\\
	&+ t(X^{2T}A^{T}AXH + X^{2T}A^{T}AHX + X^{2T}A^{T}BH \\
	&+ H^{T}X^{T}A^{T}AX^{2} + X^TH^TA^TAX^{2} + H^TB^TAX^{2}\\
	&+ X^TB^TAXH + X^TB^TAHX + X^TB^TBH \\
	&+ H^TX^TA^TBX + X^TH^TA^TBX + H^TB^TBX \\
	&+ C^TAXH + C^TAHX + C^TBH \\
	&+ H^TX^TA^TC + X^TH^TA^TC + H^TB^TC)\\
	&\\
	&+ (AX^{2}+BX+C)^{T}(AX^{2}+BX+C)
\end{array}
$$

$$
\begin{array}{rl}
Q(X+tH)^{T}Q(X+tH) &= t^{4}(AH^{2})^T(AH^{2}) \\
	&+ t^{3}(H^{2T}A^{T}(AXH + AHX + BH) + (H^{T}X^{T}A^{T} + X^{T}H^{T}A^{T} + H^{T}B^{T})AH^{2}) \\
	&\\
	&+ t^{2}((X^{2T}A^{T} + X^{T}B^{T}+ C^{T})AH^{2} + H^{2T}A^{T}(AX^{2} + BX + C) \\
	&+ (AHX+AHX+BH)^{T}(AHX+AHX+BH))\\
    &\\
	&+ t((X^{2T}A^{T} + X^TB^T + C^T)(AXH + AHX + BH) \\
	&+ (H^{T}X^{T}A^{T} + X^TH^TA^T + H^TB^T)(AX^{2} + BX + C))\\
	&\\
	&+ (AX^{2}+BX+C)^{T}(AX^{2}+BX+C)
\end{array}
$$

