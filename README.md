
<!DOCTYPE html>

<html lang="en-GB">

    <head>
       
        <title>

            Step 3: complex form input types

        </title>
    </head>
    <body>
        <h1>

            Замовляйте заказ!)

        </h1>
        <form id="contact-form" method="post" action="script.php">
            <ul>
                

<li>
	        <label for="Введіть марку">Введіть марку:</label>
	        <input type="text" name="Введіть марку" id="Введіть марку" value="" />
	      </li>
	      <li>
	        <label for="введіть колір">введіть колір:</label>
	        <input type="text" name="введіть колір" id="введіть колір" value="" />
	      </li>
	      
	      <li>
	        <label for="mailing-list"> Хочете, щоб підписатися на нашу розсилку? </label>
	        <input type="checkbox" checked="checked" id="mailing-list" value="Yes, sign me up!" />
	      </li>
	      <li>
	        <input type="submit" value="Шукати" />
	        <input type="reset" value="Зкинути все" />
	      </li>

<li>
</ul><ul></ul><ul>
	        <label for="mailing-list"> Хочете в нас зареєструватись? </label>
	        <input type="checkbox" checked="checked" id="mailing-list" value="Yes, sign me up!" />
	      </li>


	    </ul>
                <li>
                    <label for="email">

                       Введіть  Email:

                    </label>
                    <input id="email" type="text" value="" name="email"></input>
                </li>
                <li>
                    <label for="pwd">

                      Введіть пароль:

                    </label>
                    <input id="pwd" type="password" value="" name="pwd"></input>
                </li>
            </ul>
            <ul>
                <li>

                    Якого кольору ноутбуки вам подобаються?

                    <ul>
                        <li>
                            <label for="чорний">

                                чорний

                            </label>
                            <input id="чорний" type="checkbox" checked="checked" value="чорний" name="чорний"></input>
                        </li>
                        <li>
                            <label for="білий">

                                білий

                            </label>
                            <input id="білий" type="checkbox" value="білий" name="білий"></input>
                        </li>
                        <li>
                            <label for="синій">

                                синій

                            </label>
                            <input id="синій" type="checkbox" value="синій" name="синій"></input>
                        </li>
                        <li>
                            <label for="червоний">

                                червоний

                            </label>
                            <input id="червоний" type="checkbox" value="червоний" name="червоний"></input>
                        </li>
			<li>
                            <label for="жовтий">

                                жовтий

                            </label>
                            <input id="жовтий" type="checkbox" value="жовтий" name="жовтий"></input>
                        </li>
                    </ul>
                </li>
                <li>

                    Яким чином вам підходить отримати товар
                        

                    <ul>
                        <li>
                            <label for="vsat">

                                Приїду - заберу

                            </label>
                            <input id="vsat" type="radio" checked="checked" value="vsat" name="satisfaction"></input>
                        </li>
                        <li>
                            <label for="sat">

                                Посилка почтою

                            </label>
                            <input id="sat" type="radio" value="sat" name="satisfaction"></input>
                        </li>
                        <li>
                            <label for="dcare">

                                Кур'єр

                            </label>
                            <input id="dcare" type="radio" value="dcare" name="satisfaction"></input>
                        </li>
                        <li>
                            <label for="disat">

                                Автобусом

                            </label>
                            <input id="disat" type="radio" value="disat" name="satisfaction"></input>
                        </li>
                        <li>
                            <label for="vdisat">

                                "Нова почта"

                            </label>
                            <input id="vdisat" type="radio" value="vdisat" name="satisfaction"></input>
                        </li>
                    </ul>
                </li>
                <li>
                    <label for="comments">

                        Додавайте коментарі:

                    </label>
                    <textarea id="comments" rows="3" cols="25" name="comments"></textarea>
                </li>
            </ul>
            <ul>
                <li>
                    <label for="photo">

                        Загрузіть ваше фото!):

                    </label>
                    <input id="photo" type="file" value="" name="photo"></input>
                </li>
                <li>
                    <label for="location">

                        Звідки ви?:

                    </label>
                    <Select  id="location" name="location">
                        <option value="">

                            Виберіть місто!

                        </option>
                        <option value="Київ">

                            Київ

                        </option>
                        <option value="Канів">

                            Канів

                        </option>
                        <option value="черкаси">

                            Черкаси

                        </option>
                        <option value="сміла">

                            Львів

                        </option>
                        <option value="Донецьк">

                            Донецьк

                        </option>
                        <option value="Херсон">

                            Херсон

                        </option>
                    </select>
                </li>
            </ul>
            <li>
                <input type="submit" value="submit"></input>
            </li>
        </form>
    </body>

</html>
