<!DOCTYPE html>
<html>

<head>
</head>

<body>
    <h1>A convolution neural network for fruit images recogition</h1>
    <p>A convolution neural network based on <a href="http://yann.lecun.com/exdb/lenet/"><b>Lenet-5</b></a>
        , implemented by <a href="https://www.tensorflow.org/api_docs/python/tf/keras"><b>tf.Keras</b></a></p>
    <p>Structure:</p>
    <table>
        <tr>
            <th>Layer (type)</th>
            <th>Output Shape</th>
            <th>Parameters</th>
        </tr>
        <tr style = "text-align": center>
            <td>conv2d (Conv2D)</td>
            <td>(None, 148, 148, 32)</td>
            <td>896</td>
        </tr>
        <tr>
            <td>max_pooling2d (MaxPooling2D)</td>
            <td>(None, 74, 74, 32)</td>
            <td>0</td>
        </tr>
        <tr>
            <td>conv2d (Conv2D)</td>
            <td>(None, 72, 72, 64)</td>
            <td>18496</td>
        </tr>
        <tr>
            <td>max_pooling2d (MaxPooling2D)</td>
            <td>(None, 36, 36, 64)</td>
            <td>0</td>
        </tr>
        <tr>
            <td>flatten (Flatten)</td>
            <td>(None, 82944)</td>
            <td>0</td>
        </tr>
        <tr>
            <td>dense (Dense)</td>
            <td>(None, 512)</td>
            <td>0</td>
        </tr>
        <tr>
            <td>dropout (Dropout)</td>
            <td>(None, 512)</td>
            <td>0</td>
        </tr>
        <tr>
            <td>dense (Dense)</td>
            <td>(None, 4)</td>
            <td>2052</td>
        </tr>
    </table>
    <ul>
        <li>Total parameters: 42,489,284</li>
        <li>Trainable parameters: 42,489,284</li>
        <li>Non-trainable parameters: 0</li>
    </ul>
</body>

</html>
