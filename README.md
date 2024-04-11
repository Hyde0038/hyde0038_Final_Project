# Edan Hyde - hyde0038

```

function calculateBMI(weight = 90, height = 1.91) {
    let bmi = ((weight / height) / height);

    interpretBMI(bmi);
}

function interpretBMI(bmi){
    console.log(bmi.toFixed(2));
    if( bmi < 18.5 ) {
        console.log("Underweight");
    } else if ( bmi < 18.5 && bmi > 25 ) {
        console.log("Normal weight");
    } else if ( bmi >= 25 && bmi < 30 ) {
        console.log("Overweight");
    } else if ( bmi >= 30) {
        console.log("Obese");
    }
}

calculateBMI();

```

![1712848797298](https://file+.vscode-resource.vscode-cdn.net/Users/edhyde/Documents/code/mad9112/hyde0038_Final_Project/image/README/1712848797298.png)

![1712848847234](image/README/1712848847234.png)

![1712848859592](image/README/1712848859592.png)

![1712850604411](image/README/1712850604411.png)
