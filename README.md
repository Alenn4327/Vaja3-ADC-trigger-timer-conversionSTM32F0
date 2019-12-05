# Vaja3-ADC-trigger-timer-conversion-STOM32F0

<h3> Glede na vašo razvojno ploščo in razširitveno vezje s tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to?</h3>
<p>PC0</p>

<h3>Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?</h3>
<p>ADC_IN10</p>

<h3>Aktiviramo samo zeleno LED diodo na ustreznem izhodu.</h3>
<p>PC9</p>

<h3>V "Clock configuration" spremenimo APB1 Timer clock (MHz) na 16 MHz. Kaj opazite?</h3>
<p>APB1 peripheral clock se nastavi na polovico APB1 Timer clock-a, drugi
pa se nastavijo na isto frekvenco kot APB1 Timer clock.</p>

<h3>V "Configuration" kliknemo gumb za TIM1, ki je v polju "Control". Časovniku bi radi spremenili frekvenco na 1 kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju "Prescaler" (PSC-16 bit value). Koliko znaša ta vrednost?</h3>
<p>16000</p>

<h3>Branje vrednosti želimo prikazati z utripanjem zelene LED diode na STM32F0 ploščici. Uporabite metodo "TogglePin" iz HAL knjižnice in zapišite ukaz.</h3>
<p>HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);</p>

<h3>Komentar</h3>
<p>Težav nisva imela.</p>
