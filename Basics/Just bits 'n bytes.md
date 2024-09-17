<span style = "font-size:20px">This is a very interesting fact:<p style = "padding:1pt"></p> 2<sup>n</sup> - 1 = 2<sup>n-1</sup> + 2<sup>n-2</sup> + 2<sup>n-3</sup>... + 2<sup>2</sup> + 2<sup>1</sup> + 2<sup>0</sup><p style = "padding:1pt"></p>Let's proff that using method of math induction.</span>
<span style = "font-size:20px">First thing first, we prove it for <i>n</i> = 3. <p style = "padding:1pt"></p> 2<sup>3</sup> - 1 = 7 = 2<sup>2</sup> + 2<sup>1</sup> + 2 <sup>0</sup><p style = "padding:1pt"></p>Let's it be truth for 2<sup>x-1</sup>. Prove that it truth for 2<sup>x</sup>. We got:<p style = "padding:1pt"></p>
2<sup>x</sup> - 1 = 2<sup>x-1</sup> + ... +  2<sup>0</sup><i>  (1)</i><p></p>
2<sup>x-1</sup> - 1 = 2<sup>x-2</sup> + ... +  2<sup>0</sup><i>  (2)</i><p style = "padding:1pt"></p>Let's subtract <i>(2)</i> from <i>(1)</i>: <p style = "padding:1pt"></p>
2<sup>x</sup> - 2<sup>x-1</sup> = 2<sup>x-1</sup><p></p>
2<sup>x</sup> = 2 * 2<sup>x-1</sup><p></p>
2<sup>x</sup> = 2<sup>x</sup><p style = "padding:1pt"></p>So <i>2<sup>x</sup> = 2<sup>x</sup></i> is truth, what was required to prove.</span>
<span style = "font-size: 20px">Why did I talk about it. One byte is an eight bits. <p></p>
11111111<sub>2</sub> = 2<sup>7</sup> + 2<sup>6</sup> + 2<sup>5</sup> + 2<sup>4</sup> + 2<sup>3</sup> + 2<sup>2</sup> + 2<sup>1</sup> + 2<sup>0</sup> = 2<sup>8</sup> - 1 = 255<sub>10</sub><p></p>But first bit is "reserved" for sign. So we get 7 free bits. This means that in one byte we can put a maximum of 2<sup>7</sup> - 1 = 127. The minimum is -128. If there weren't 0, we could put a maximum of 128.</span>
