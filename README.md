# sampling_credit_card
This file gives accuracy score for different sampling techniques(on inbalanced data) trained on different models as given below
<ul>
    <li>
        Sampling Techniques
        <ol>
            <li>
                Under Sampling
            </li>
            <li>
                Over Sampling
            </li>
            <li>
                Tomek links
            </li>
            <li>
                SMOTE
            </li>
            <li>
                Near Miss
            </li>
        </ol>
    </li>
    <li>
        Modelling techniques
        <ol>
            <li>
                XGB
            </li>
            <li>
                Random Forest
            </li>
            <li>
                Decision Tree
            </li>
            <li>
                SVM
            </li>
            <li>
                Naive Bayesian
            </li>
        </ol>
    </li>
</ul>
<h1>Result table</h1>
|<table>
    <tr>
        <td>Model\Sampling</td>
        <td>Under sampling</td>
        <td>Over sampling</td>
        <td>Tomek Links</td>
        <td>SMOTE</td>
        <td>Near Miss</td>
    </tr>
    <tr>
        <td>XGB</td>
        <td>0.5</td>
        <td>0.995208</td>
        <td>0.990446</td>
        <td>0.984026</td>
        <td>0.75</td>
    </tr>
    <tr>
        <td>Random Forest</td>
        <td>0.625</td>
        <td>0.998403</td>
        <td>0.990446</td>
        <td>0.998361</td>
        <td>0.75</td>
    </tr>
    <tr>
        <td>Decision Tree</td>
        <td>0.375</td>
        <td>0.992013</td>
        <td>0.980892</td>
        <td>0.966454</td>
        <td>0.75</td>
    </tr>
    <tr>
        <td>SVM</td>
        <td>0.5</td>
        <td>0.92492</td>
        <td>0.990446</td>
        <td>0.92492</td>
        <td>0.875</td>
    </tr>
    <tr>
        <td>Naïve Bayesian</td>
        <td>0.75</td>
        <td>0.920128</td>
        <td>0.987261</td>
        <td>0.878594</td>
        <td>0.25</td>
    </tr>
</table>
