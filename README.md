# Raspberry-Pi-Power-Button

## Psuedo Code to shutdown PI

```python
button = gpiopin
while True:
    if button is pressed:
        shutdown pi
        
```

# Startup Raspberry Pi

## Psuedo Code to startup PI

```python
button = gpiopin
while True:
    if button is pressed:
        startup pi
        
```


We will use gpio pin 3 (SCL) and any ground pin you like to connect a with button. 

If raspberry Pi is running then press of the button will shutdown PI.
If it's in shutdown state then press of the button will startup raspberry PI.

        
        
        
        
