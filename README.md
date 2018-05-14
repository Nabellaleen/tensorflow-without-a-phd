Code samples from the "Tensorflow without a PhD" series by Martin Gorner [https://twitter.com/martin_gorner](@martin_gorner).

## Featured sample

[tensorflow-rl-pong](tensorflow-rl-pong) fome the Google I/O 2018 session "Tensorflow and deep reinforcement learning, without a PhD".<br/>
Other samples from the "Tensorflow without a PhD" series will soon be migrated to this repository.

## Tensorflow and deep learning without a PhD series by Martin Gorner [https://twitter.com/martin_gorner](@martin_gorner).

A crash course in six episodes for software developers who want to learn machine learning, with examples, theoretical concepts,
and engineering tips, tricks and best practices to build and train the neural networks that solve your problems.

<table border=0 width=100%>
    <tr>
        <td width="50%"><img alt="Tensorflow and deep learning without a PhD" src="tensorflow-rl-pong/images/flds1.png"/></td>
        <td width="50%">
            <div align="center">
                     <a href="https://youtu.be/u4alGiomYP4">video</a> |
                     <a href="https://docs.google.com/presentation/d/1TVixw6ItiZ8igjp6U17tcgoFrLSaHWQmMOwjlgQY9co/pub?slide=id.p">slides</a> |
                     <a href="https://codelabs.developers.google.com/codelabs/cloud-tensorflow-mnist/#0">codelab</a> |
                     <a href="https://github.com/martin-gorner/tensorflow-mnist-tutorial">code</a><br/><br/></div>
                     <p>The basics of building neural networks for software engineers. Neural weights and biases, activation functions, softmax, cross-entropy, supervised learning and gradient descent.
                     Tips and best practices for efficient training: learning rate decay, dropout regularisation and the intricacies of overfitting. Dense and convolutional neural networks. This session starts with low-level
                     Tensorflow and also has a sample of high-level Tensorflow code using layers and Datasets. Duration: 55 min</p></td>
    </tr>
    <tr>
        <td width="50%"><div align="center">
                                          <a href="https://youtu.be/vq2nnJ4g6N0?t=76m">video</a> |
                                          <a href="https://docs.google.com/presentation/d/18MiZndRCOxB7g-TcCl2EZOElS5udVaCuxnGznLnmOlE/pub?slide=id.g1245051c73_0_25">slides</a> |
                                          <a href="https://github.com/martin-gorner/tensorflow-mnist-tutorial/blob/master/README_BATCHNORM.md">code</a><br/><br/></div>
                                          <p>What is batch normalisation, how to use it appropriately and how to see if it is working or not. Duration: 25 min</p></td>
        <td width="50%"><img alt="The superpower: batch normalization" src="tensorflow-rl-pong/images/flds2.png"/></td>
    </tr>
    <tr>
        <td border=0 width="50%"><img alt="Tensorflow, deep learning and recurrent neural networks, without a PhD" src="tensorflow-rl-pong/images/flds3.png"/></td>
        <td border=0 width="50%">
            <div align="center">
                 <a href="https://youtu.be/fTUwdXUFfI8">video</a> |
                 <a href="https://docs.google.com/presentation/d/18MiZndRCOxB7g-TcCl2EZOElS5udVaCuxnGznLnmOlE/pub?slide=id.p">slides</a> |
                 <a href="https://github.com/martin-gorner/tensorflow-rnn-tutorial">codelab</a> |
                 <a href="https://github.com/martin-gorner/tensorflow-rnn-shakespeare">code</a><br/><br/></div>
                 <p> RNN basics: the RNN cell a state machine, training and unrolling (backpropagation through time).
                 More advanced RNN cells: LSTM and GRU cells. Application to language modeling and generation. Tensorflow APIs for RNNs. Duration: 55 min</p></td>
    </tr>
    <tr>
        <td width="50%"><div align="center">
                  <a href="https://youtu.be/vaL1I2BD_xY">video</a> |
                  <a href="https://docs.google.com/presentation/d/19u0Tm0JHL5tpzyarLILvy4qLSuDBFNNx2hwSvZsFPI0/pub">slides</a> |
                  code: soon<br/><br/></div>
                  <p>Convolutional neural network architectures for image processing. Convnet basics, convolution filters and how to stack them. 
                  Learnings from the Inception model: modules and parallel convolutions, 1x1 convolutions, ... A simple modern convnet architecture: Squeezenet.
                  Convenets for detection: the YOLO (You Look Only Once) architecture. Full-scale model training and serving with Tensorflow's Estimator API on Google Cloud ML Engine.
                  Duration: 55 min</p></td>
        <td width="50%"><img alt="Tensorflow, deep learning and modern convnets, without a PhD" src="tensorflow-rl-pong/images/flds4.png"/></td>
    </tr>
    <tr>
            <td border=0 width="50%"><img alt="Tensorflow, deep learning and modern RNN architectures, without a PhD" src="tensorflow-rl-pong/images/flds5.png"/></td>
            <td border=0 width="50%">
                <div align="center">
                     <a href="https://youtu.be/pzOzmxCR37I">video</a> |
                     <a href="https://docs.google.com/presentation/d/17gLPozfb-l3WCR8FnejNJD9tEI_igTq1YqIXzCtOR14/pub">slides</a> |
                     code: soon<br/><br/></div>
                     <p>Advanced RNN architectures for natural language processing. Word embeddings, text classification,
                     bidirectional models, sequence to sequence models for trqnslqtion. Attention mechanisms. This session also explores
                     Tensorflow's powerful seq2seq API. Co-author: Nithum Thain. Duration: 55 min</p></td>
    </tr>
    <tr>
        <td width="50%"><div align="center">
            <a href="https://youtu.be/t1A3NTttvBA">video</a> |
            <a href="https://docs.google.com/presentation/d/1qLVvgKxZlM6_oOZ4-ZoOAB0wTh2IdhbFvuBhsMvmK9I/pub">slides</a> |
            <a href="tensorflow-rl-pong">code</a><br/><br/></div>
            <p>
            A neural network trained to play the game of Pong for just the pixels of the game.
            Uses reinforcement learning and policy gradients. The approach can be generalized to
            other problem involving a non-differentiable step that cannot be trained using traditional supervised learning techniques.
            A practical application: neural architecture search - neural networks designing neural networks. Co-author: Yu-Han Liu. Duration: 40 min</p></td>
        <td width="50%"><img alt="Tensorflow and deep reinforcement learning, without a PhD" src="tensorflow-rl-pong/images/flds6.png"/></td>
        </tr>
</table>

*Disclaimer: This is not an official Google product but sample code provided for an educational purpose*