<h3>Codebook for output of run_analysis.R<h3>
<h4>Bill Wolf<h4>

<p>The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals time.acc.XYZ and time.gyro.xyz. These time domain signals (prefix 'time' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (time.body.acc.xyz and time.gravity.acc.xya) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. </p>

<p>Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (time.body.acc.jerk.xyz and time.body.gyro.jerk.xyz). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (time.body.acc.mag, time.gravity.acc.mag, time.body.acc.jerk.mag, time.body.gyro.mag, time.body.gyro.jerk.mag).</p> 

<p>Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing freq.body.acc.xyz, freq.body.acc.jerk.xyz, freq.body.gyro.xyz, freq.body.acc.jerk.mag, freq.body.gyro.mag, freq.body.gyro.jerk.mag. (Note the 'freq' to indicate frequency domain signals).</p> 

<p>'.xyz' is used to denote 3-axial signals in the X, Y and Z directions.</p>
<p>'.mean' is used to denote mean value and '.std' to denote standard deviation</p>

<table>
<tr><th>variable name</th><th>definition</th><th>R type</th><th>min value seen</th><th>max value seen</th></tr>
<tr><td>time.body.acc.mean.x</td><td>def</td><td>numeric</td><td>0.26229464948342</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.body.acc.mean.y</td><td>def</td><td>numeric</td><td>-0.0259232890342181</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.body.acc.mean.z</td><td>def</td><td>numeric</td><td>-0.120537934670272</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.body.acc.std.x</td><td>def</td><td>numeric</td><td>-0.98443471156873</td><td>-0.0126895730832639</td></tr>
<tr><td>time.body.acc.std.y</td><td>def</td><td>numeric</td><td>-0.943507185574074</td><td>-0.0126895730832639</td></tr>
<tr><td>time.body.acc.std.z</td><td>def</td><td>numeric</td><td>-0.948069300024897</td><td>-0.0126895730832639</td></tr>
<tr><td>time.grav.acc.mean.x</td><td>def</td><td>numeric</td><td>-0.375021333827161</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.grav.acc.mean.y</td><td>def</td><td>numeric</td><td>-0.281377193548575</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.grav.acc.mean.z</td><td>def</td><td>numeric</td><td>-0.161179728291022</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.grav.acc.std.x</td><td>def</td><td>numeric</td><td>-0.988015176652676</td><td>-0.0126895730832639</td></tr>
<tr><td>time.grav.acc.std.y</td><td>def</td><td>numeric</td><td>-0.972505174787234</td><td>-0.0126895730832639</td></tr>
<tr><td>time.grav.acc.std.z</td><td>def</td><td>numeric</td><td>-0.959434177692308</td><td>-0.0126895730832639</td></tr>
<tr><td>time.body.acc.jerk.mean.x</td><td>def</td><td>numeric</td><td>0.0701731261988856</td><td>-0.0126895730832639</td></tr>      
<tr><td>time.body.acc.jerk.mean.y</td><td>def</td><td>numeric</td><td>0.000479281129661539</td><td>-0.0126895730832639</td></tr>      
<tr><td>time.body.acc.jerk.mean.z</td><td>def</td><td>numeric</td><td>-0.0196719912994306</td><td>-0.0126895730832639</td></tr>      
<tr><td>time.body.acc.jerk.std.x</td><td>def</td><td>numeric</td><td>-0.984997226336522</td><td>-0.0126895730832639</td></tr>     
<tr><td>time.body.acc.jerk.std.y</td><td>def</td><td>numeric</td><td>-0.973883160517726</td><td>-0.0126895730832639</td></tr>     
<tr><td>time.body.acc.jerk.std.z</td><td>def</td><td>numeric</td><td>-0.982296486972425</td><td>-0.0126895730832639</td></tr>     
<tr><td>time.body.gyro.mean.x</td><td>def</td><td>numeric</td><td>-0.0840345434632895</td><td>-0.0126895730832639</td></tr>  
<tr><td>time.body.gyro.mean.y</td><td>def</td><td>numeric</td><td>-0.0954921154823529</td><td>-0.0126895730832639</td></tr>  
<tr><td>time.body.gyro.mean.z</td><td>def</td><td>numeric</td><td>0.0598938080367487</td><td>-0.0126895730832639</td></tr>  
<tr><td>time.body.gyro.std.x</td><td>def</td><td>numeric</td><td>-0.981022213218908</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.body.gyro.std.y</td><td>def</td><td>numeric</td><td>-0.966708127310073</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.body.gyro.std.z</td><td>def</td><td>numeric</td><td>-0.963509228024691</td><td>-0.0126895730832639</td></tr> 
<tr><td>time.body.gyro.jerk.mean.x</td><td>def</td><td>numeric</td><td>-0.112117464583562</td><td>-0.0126895730832639</td></tr>       
<tr><td>time.body.gyro.jerk.mean.y</td><td>def</td><td>numeric</td><td>-0.051263979292845</td><td>-0.0126895730832639</td></tr>       
<tr><td>time.body.gyro.jerk.mean.z</td><td>def</td><td>numeric</td><td>-0.0638498197415123</td><td>-0.0126895730832639</td></tr>       
<tr><td>time.body.gyro.jerk.std.x</td><td>def</td><td>numeric</td><td>-0.985705127658976</td><td>-0.0126895730832639</td></tr>      
<tr><td>time.body.gyro.jerk.std.y</td><td>def</td><td>numeric</td><td>-0.986502338745076</td><td>-0.0126895730832639</td></tr>      
<tr><td>time.body.gyro.jerk.std.z</td><td>def</td><td>numeric</td><td>-0.984782526095679</td><td>-0.0126895730832639</td></tr>      
<tr><td>time.body.acc.mag.mean</td><td>def</td><td>numeric</td><td>-0.95464392144063</td><td>-0.0126895730832639</td></tr>   
<tr><td>time.body.acc.mag.std</td><td>def</td><td>numeric</td><td>-0.946534779481637</td><td>-0.0126895730832639</td></tr>  
<tr><td>time.grav.acc.mag.mean</td><td>def</td><td>numeric</td><td>-0.95464392144063</td><td>-0.0126895730832639</td></tr>   
<tr><td>time.grav.acc.mag.std</td><td>def</td><td>numeric</td><td>-0.946534779481637</td><td>-0.0126895730832639</td></tr>  
<tr><td>time.body.acc.jerk.mag.mean</td><td>def</td><td>numeric</td><td>-0.98244444337085</td><td>-0.0126895730832639</td></tr>        
<tr><td>time.body.acc.jerk.mag.std</td><td>def</td><td>numeric</td><td>-0.978907079240293</td><td>-0.0126895730832639</td></tr>       
<tr><td>time.body.gyro.mag.mean</td><td>def</td><td>numeric</td><td>-0.946724138930782</td><td>-0.0126895730832639</td></tr>    
<tr><td>time.body.gyro.mag.std</td><td>def</td><td>numeric</td><td>-0.951199015615082</td><td>-0.0126895730832639</td></tr>   
<tr><td>time.body.gyro.jerk.mag.mean</td><td>def</td><td>numeric</td><td>-0.987880071435003</td><td>-0.0126895730832639</td></tr>         
<tr><td>time.body.gyro.jerk.mag.std</td><td>def</td><td>numeric</td><td>-0.98460762855937</td><td>-0.0126895730832639</td></tr>        
<tr><td>freq.body.acc.mean.x</td><td>def</td><td>numeric</td><td>-0.983091966702307</td><td>-0.0126895730832639</td></tr> 
<tr><td>freq.body.acc.mean.y</td><td>def</td><td>numeric</td><td>-0.952678416904835</td><td>-0.0126895730832639</td></tr> 
<tr><td>freq.body.acc.mean.z</td><td>def</td><td>numeric</td><td>-0.960018019984568</td><td>-0.0126895730832639</td></tr> 
<tr><td>freq.body.acc.std.x</td><td>def</td><td>numeric</td><td>-0.985859786930745</td><td>-0.0126895730832639</td></tr>
<tr><td>freq.body.acc.std.y</td><td>def</td><td>numeric</td><td>-0.942460971074588</td><td>-0.0126895730832639</td></tr>
<tr><td>freq.body.acc.std.z</td><td>def</td><td>numeric</td><td>-0.945643635450566</td><td>-0.0126895730832639</td></tr>
<tr><td>freq.body.acc.jerk.mean.x</td><td>def</td><td>numeric</td><td>-0.985188769302195</td><td>-0.0126895730832639</td></tr>      
<tr><td>freq.body.acc.jerk.mean.y</td><td>def</td><td>numeric</td><td>-0.973988189836804</td><td>-0.0126895730832639</td></tr>      
<tr><td>freq.body.acc.jerk.mean.z</td><td>def</td><td>numeric</td><td>-0.97956197226224</td><td>-0.0126895730832639</td></tr>      
<tr><td>freq.body.acc.jerk.std.x</td><td>def</td><td>numeric</td><td>-0.98618495368036</td><td>-0.0126895730832639</td></tr>     
<tr><td>freq.body.acc.jerk.std.y</td><td>def</td><td>numeric</td><td>-0.975750855391109</td><td>-0.0126895730832639</td></tr>     
<tr><td>freq.body.acc.jerk.std.z</td><td>def</td><td>numeric</td><td>-0.983670821046708</td><td>-0.0126895730832639</td></tr>     
<tr><td>freq.body.gyro.mean.x</td><td>def</td><td>numeric</td><td>-0.977267261395611</td><td>-0.0126895730832639</td></tr>  
<tr><td>freq.body.gyro.mean.y</td><td>def</td><td>numeric</td><td>-0.972457592965672</td><td>-0.0126895730832639</td></tr>  
<tr><td>freq.body.gyro.mean.z</td><td>def</td><td>numeric</td><td>-0.964184423173868</td><td>-0.0126895730832639</td></tr>  
<tr><td>freq.body.gyro.std.x</td><td>def</td><td>numeric</td><td>-0.982333273978616</td><td>-0.0126895730832639</td></tr> 
<tr><td>freq.body.gyro.std.y</td><td>def</td><td>numeric</td><td>-0.964033658897017</td><td>-0.0126895730832639</td></tr> 
<tr><td>freq.body.gyro.std.z</td><td>def</td><td>numeric</td><td>-0.966725247165638</td><td>-0.0126895730832639</td></tr> 
<tr><td>freq.body.acc.mag.mean</td><td>def</td><td>numeric</td><td>-0.955868098520462</td><td>-0.0126895730832639</td></tr>   
<tr><td>freq.body.acc.mag.std</td><td>def</td><td>numeric</td><td>-0.949601613473977</td><td>-0.0126895730832639</td></tr>  
<tr><td>freq.body.acc.jerk.mag.mean</td><td>def</td><td>numeric</td><td>-0.978684370388295</td><td>-0.0126895730832639</td></tr>        
<tr><td>freq.body.acc.jerk.mag.std</td><td>def</td><td>numeric</td><td>-0.978154770658413</td><td>-0.0126895730832639</td></tr>       
<tr><td>freq.body.gyro.mag.mean</td><td>def</td><td>numeric</td><td>-0.964296113911086</td><td>-0.0126895730832639</td></tr>    
<tr><td>freq.body.gyro.mag.std</td><td>def</td><td>numeric</td><td>-0.951641735873945</td><td>-0.0126895730832639</td></tr>   
<tr><td>freq.body.gyro.jerk.mag.mean</td><td>def</td><td>numeric</td><td>-0.985335632976927</td><td>-0.0126895730832639</td></tr>         
<tr><td>freq.body.gyro.jerk.mag.std</td><td>def</td><td>numeric</td><td>-0.984491355740011</td><td>-0.0126895730832639</td></tr> 
</table>