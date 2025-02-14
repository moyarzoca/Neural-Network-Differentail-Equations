The code is able to solve the trace of the Einstein equations of Kerr in Kerr-Schild coordinates. It reads\
$$(r^{2}+a^{2}\cos^{2}\theta)\frac{\partial^{2}F}{\partial r^{2}}+4r\frac{\partial F}{\partial r}+2F =0$$\
where $F = F(r,\theta)$ is the metric function. With the appropriated boundary conditions it implies all the Einstein's equations.

The neural network is a feedforward neural network with two hidden layers. The loss function is computed by computing the differential equation displayed above. 
To compute the derivative I compute by hand the derivative with respect to the variables. I construted a recursive formula for the derivative of the neural network. You can see the details in Section 6.2 of my personal notes available in the PDF Marcelo_notes_Neural_Networks.pdf. 

