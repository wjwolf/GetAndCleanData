<h3>Codebook for output of run_analysis.R<h3>
<h4>Bill Wolf<h4>

<p>This codebook describes data tha is a transformation of original data produces by:</p>
<code>
[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012
</code>

<p>Here are the variables produced by my run_analysis.R:</p>

<table>
<tr><th>variable name</th><th>definition</th><th>R type</th><th>max value seen (activity)</th><th>max value seen (subject)</th></tr>
<tr><td>time.body.acc.mean.x</td><td>see below</td><td>numeric</td><td>0.288137227760313</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.mean.y</td><td>see below</td><td>numeric</td><td>-0.0126895730832639</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.mean.z</td><td>see below</td><td>numeric</td><td>-0.105517003220878</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.std.x</td><td>see below</td><td>numeric</td><td>0.100766330932127</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.std.y</td><td>see below</td><td>numeric</td><td>0.0595486228783642</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.std.z</td><td>see below</td><td>numeric</td><td>-0.175449700484728</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.mean.x</td><td>see below</td><td>numeric</td><td>0.941479635262329</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.mean.y</td><td>see below</td><td>numeric</td><td>0.622270362899691</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.mean.z</td><td>see below</td><td>numeric</td><td>0.55561247407572</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.std.x</td><td>see below</td><td>numeric</td><td>-0.943319727953189</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.std.y</td><td>see below</td><td>numeric</td><td>-0.925549271962435</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.std.z</td><td>see below</td><td>numeric</td><td>-0.901905618180052</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.mean.x</td><td>see below</td><td>numeric</td><td>0.0892266917679481</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.mean.y</td><td>see below</td><td>numeric</td><td>0.0115061924659823</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.mean.z</td><td>see below</td><td>numeric</td><td>-0.00231938614930952</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.std.x</td><td>see below</td><td>numeric</td><td>-0.0338826468930654</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.std.y</td><td>see below</td><td>numeric</td><td>-0.0736744063550434</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.std.z</td><td>see below</td><td>numeric</td><td>-0.388666069444772</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.mean.x</td><td>see below</td><td>numeric</td><td>0.00682449600215674</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.mean.y</td><td>see below</td><td>numeric</td><td>-0.0529928638977233</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.mean.z</td><td>see below</td><td>numeric</td><td>0.125885141252623</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.std.x</td><td>see below</td><td>numeric</td><td>-0.333817475057255</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.std.y</td><td>see below</td><td>numeric</td><td>-0.339631376954339</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.std.z</td><td>see below</td><td>numeric</td><td>-0.237136760675842</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.jerk.mean.x</td><td>see below</td><td>numeric</td><td>-0.0728532273938407</td><td>-0.0148081545344921</td></tr>                
<tr><td>time.body.gyro.jerk.mean.y</td><td>see below</td><td>numeric</td><td>-0.038198085408019</td><td>-0.0148081545344921</td></tr>                
<tr><td>time.body.gyro.jerk.mean.z</td><td>see below</td><td>numeric</td><td>-0.0507555280236061</td><td>-0.0148081545344921</td></tr>                
<tr><td>time.body.gyro.jerk.std.x</td><td>see below</td><td>numeric</td><td>-0.37622140274036</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.jerk.std.y</td><td>see below</td><td>numeric</td><td>-0.465943810555121</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.jerk.std.z</td><td>see below</td><td>numeric</td><td>-0.326455992480064</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.mag.mean</td><td>see below</td><td>numeric</td><td>0.101249699851558</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.mag.std</td><td>see below</td><td>numeric</td><td>0.116488914352198</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.mag.mean</td><td>see below</td><td>numeric</td><td>0.101249699851558</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.grav.acc.mag.std</td><td>see below</td><td>numeric</td><td>0.116488914352198</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.acc.jerk.mag.mean</td><td>see below</td><td>numeric</td><td>-0.111801821250135</td><td>-0.0148081545344921</td></tr>                 
<tr><td>time.body.acc.jerk.mag.std</td><td>see below</td><td>numeric</td><td>-0.011220665881458</td><td>-0.0148081545344921</td></tr>                
<tr><td>time.body.gyro.mag.mean</td><td>see below</td><td>numeric</td><td>-0.129785639782795</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.mag.std</td><td>see below</td><td>numeric</td><td>-0.251427800988919</td><td>-0.0148081545344921</td></tr>               
<tr><td>time.body.gyro.jerk.mag.mean</td><td>see below</td><td>numeric</td><td>-0.416891551237909</td><td>-0.0148081545344921</td></tr>                  
<tr><td>time.body.gyro.jerk.mag.std</td><td>see below</td><td>numeric</td><td>-0.440929331631124</td><td>-0.0148081545344921</td></tr>                 
<tr><td>freq.body.acc.mean.x</td><td>see below</td><td>numeric</td><td>0.035259668648926</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.mean.y</td><td>see below</td><td>numeric</td><td>0.0566826541965861</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.mean.z</td><td>see below</td><td>numeric</td><td>-0.21372923278293</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.std.x</td><td>see below</td><td>numeric</td><td>0.121937984843535</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.std.y</td><td>see below</td><td>numeric</td><td>-0.0082336714233357</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.std.z</td><td>see below</td><td>numeric</td><td>-0.146601790497137</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.mean.x</td><td>see below</td><td>numeric</td><td>-0.0722967761178656</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.mean.y</td><td>see below</td><td>numeric</td><td>-0.116380593184566</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.mean.z</td><td>see below</td><td>numeric</td><td>-0.333190280461238</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.std.x</td><td>see below</td><td>numeric</td><td>-0.0821905158144886</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.std.y</td><td>see below</td><td>numeric</td><td>-0.0908699078702335</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.std.z</td><td>see below</td><td>numeric</td><td>-0.443554664639787</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.mean.x</td><td>see below</td><td>numeric</td><td>-0.217922875601003</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.mean.y</td><td>see below</td><td>numeric</td><td>-0.317592694113158</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.mean.z</td><td>see below</td><td>numeric</td><td>-0.16562514453862</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.std.x</td><td>see below</td><td>numeric</td><td>-0.375127467913848</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.std.y</td><td>see below</td><td>numeric</td><td>-0.29318182767215</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.std.z</td><td>see below</td><td>numeric</td><td>-0.292041341940868</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.mag.mean</td><td>see below</td><td>numeric</td><td>0.142849426284481</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.mag.std</td><td>see below</td><td>numeric</td><td>-0.0754251669550853</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.acc.jerk.mag.mean</td><td>see below</td><td>numeric</td><td>0.00476245916278094</td><td>-0.0148081545344921</td></tr>                 
<tr><td>freq.body.acc.jerk.mag.std</td><td>see below</td><td>numeric</td><td>-0.0422714225290824</td><td>-0.0148081545344921</td></tr>                
<tr><td>freq.body.gyro.mag.mean</td><td>see below</td><td>numeric</td><td>-0.289525832505356</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.mag.std</td><td>see below</td><td>numeric</td><td>-0.361230992213905</td><td>-0.0148081545344921</td></tr>               
<tr><td>freq.body.gyro.jerk.mag.mean</td><td>see below</td><td>numeric</td><td>-0.438007290282333</td><td>-0.0148081545344921</td></tr>                  
<tr><td>freq.body.gyro.jerk.mag.std</td><td>see below</td><td>numeric</td><td>-0.486442976081671</td><td>-0.0148081545344921</td></tr>                 
</table>

<p>Each variable derives from data found in the original study, however both the variable names and values are the result of transformation</p>

<p>The variable names were transformed as follows:
<ul>
<li>original study variables began with 't' or 'f' to denote time or frequency domain values. These are remapped here to 'time' and 'freq'</li>
<li>original study variables contained 'Body' or 'Grav' to denote motion components body or gravity. These are remapped here to 'body' and 'grav'</li>
<li>original study variables contained 'Acc' or 'Gyro' to denote source accelerometer or gyroscope. These are remapped here to 'acc' and 'gyro'</li>
<li>some original study variables contained 'Jerk' to denote a derived value as described below. These are remapped here to 'jerk'</li>
<li>original study variables contained 'Mean()' or 'Sd()' to denote mean or standard deviation values. These are remapped here to 'mean' and 'std'</li>
<li>some original study variables contained a suffix of X,Y,Z to denote an axial component. These are remapped here to 'x','y','z'</li>
</ul>

<p>The values  were transformed as follows:</p>
<ul>original study test and training data sets were combined into a single data set</ul>
<ul>per assignment instructions I calculated the average value of the measurements with the same activity and sample values</p>
<ul>the acitivty values are WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING</ul> 
<ul>the sample values are 1 to 30 (e.g. 1, 2, 3, ... 30)</ul>
<ul>these average values are presented in my data set which is a matrix where the row names are the activity and sample labels, and the colum names are the variables shown in the table above</p>

<br>

<p>Here is additional background information from the original study</p>

<p>The experimenters worked with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. </p>

<p>The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used.  </p>

<p>The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals time.acc.xyz and time.gyro.xyz. These time domain signals (prefix 'time' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (time.body.acc.xyz and time.gravity.acc.xya) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. </p>

<p>Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (time.body.acc.jerk.xyz and time.body.gyro.jerk.xyz). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (time.body.acc.mag, time.gravity.acc.mag, time.body.acc.jerk.mag, time.body.gyro.mag, time.body.gyro.jerk.mag).</p> 

<p>Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing freq.body.acc.xyz, freq.body.acc.jerk.xyz, freq.body.gyro.xyz, freq.body.acc.jerk.mag, freq.body.gyro.mag, freq.body.gyro.jerk.mag. (Note the 'freq' to indicate frequency domain signals).</p> 

<p>'.xyz' is used to denote 3-axial signals in the X, Y and Z directions.</p>
<p>'.mean' is used to denote mean value and '.std' to denote standard deviation</p>

