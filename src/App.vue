<template>

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Портал Виртуальные миры</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
</head>
<body>
    <div class="page">
        <div class="page-line">
            <nav class="page-line__wrap-a">
                <a href="" class="page-line__a">Lorem ipsum</a>
                <a href="" class="page-line__a">Lorem ipsum</a>
                <a href="" class="page-line__a">Lorem ipsum</a>
                <a href="" class="page-line__a">Lorem ipsum</a>
                <a href="" class="page-line__a">Lorem ipsum</a>
            </nav>
            <div class="page-line__wrap-soсial-media">
                <a href=""><img :src="images.telegram" class="icon_social_media"></a>
                <a href=""><img :src="images.facebook" class="icon_social_media"></a>
                <a href=""><img :src="images.vk" class="icon_social_media"></a>
                <a href=""><img :src="images.instagram" class="icon_social_media"></a>
                <a href=""><img :src="images.youtube" class="icon_social_media"></a>
            </div>
            <div class="page-line__wrap-logo">
                <p id="institute-description-p" class="page-line__p">Институт Математики <br> И Информационных<br>Технологий им.<br>Профессора<br>Н.И. Червякова</p>
                <img :src="images.iitt_logo" id="institute-logo-img">
            </div>
        </div>
        <div class="page-line">
            <h1 class="text_uppercase font_bold">
            Портал Северо-Кавказского Федерального Университета
            </h1>
        </div>
        <div class="page-line">
            <p class="text_uppercase font_blue" id="virtual-worlds-title">Виртуальные миры</p>
            <div class="search-bar">
                <form method="post" class="search-bar__form">
                    <input type="text" class="input_text" placeholder="Поиск">
                    <input type="submit" value="&#128269;" class="input_submit">
                </form>
                <div class="search-bar__lang-icons">
                    <a href="" class="link-cion"><img :src="images.russian_flag" class="lang_icon"></a>
                    <p id="lang-icons-divide-line">|</p>
                    <a href="" class="link-icon"><img :src="images.uk_flag" class="lang_icon"></a>
                </div>    
            </div>
        </div>
    </div>
    <nav class="site-menu">
        <div class="site-menu__wrap">
            <a href="" class="site-menu__menu-option">Главная (о нас)</a>
            <a href="" class="site-menu__menu-option">Курсы</a>
            <a href="" class="site-menu__menu-option">Родителям</a>
            <a href="" class="site-menu__menu-option">Слушателям</a>
            <a href="" class="site-menu__menu-option">Учеба</a>
            <a href="" class="site-menu__menu-option">Видеоуроки</a>
            <a href="" class="site-menu__menu-option">А вы это знали?</a>
        </div>
    </nav>
    <div class="page">
        <div class="page-line">
            <div class="page__portal-desc">
                <h2>О портале</h2>
                <p>Виртуальные миры - это онлайн-университет.<br>
                У нас прикладные курсы и программы от главных экспертов рынка,<br> актуальные подходы к обучению, работа
                над реальными проектами,<br> стажировки и трудоустройство в крупнейшие компании страны.</p>
            </div>
            <img :src="images.ncfu_logo" id="ncfu-logo">
        </div>
        <div class="page-line">
            <div class="page-line__table">
                <div class="page-line__table-wrapper">
                <h2>Доступные курсы</h2>
                <table class="table-courses">
                    <tr>
                        <td>
                            <a class="course-link" href=""><h2>Заголовок</h2></a>
                            <p>Lorem ipsum</p>
                        </td>
                        <td>
                            <a class="course-link" href=""><h2>Заголовок</h2></a>
                            <p>Lorem ipsum</p>
                        </td>
                        <td>
                            <a class="course-link" href=""><h2>Заголовок</h2></a>
                            <p>Lorem ipsum</p>
                        </td>
                    </tr>
                </table>
                </div>
            </div>
            <div class="page-line__table-wrapper">
            <div class="blue_line"></div>
            <table class="table-calendar">
                <tr>
                    <td>
                        <p class="calendar_date">26 августа</p>
                    </td>
                    <td>
                        <p class="calendar_info">Некое событие</p>
                    </td>
                </tr>
                <tr>
                    <td>
                        <p class="calendar_date">19 сентября</p>
                    </td>
                    <td>
                        <p class="calendar_info">Некое событие</p>
                    </td>
                </tr>
                <tr>
                    <td>
                        <p class="calendar_date">16 октября</p>
                    </td>
                    <td>
                        <p class="calendar_info">Некое событие</p>
                    </td>
                </tr>
                <tr>
                    <td>
                        <p class="calendar_date">6 ноября</p>
                    </td>
                    <td>
                        <p class="calendar_info">Некое событие</p>
                    </td>
                </tr>
                <tr>
                    <td></td>
                    <td>
                        <button class="button-all-events">Все события</button>
                    </td>
                </tr>
                </table>
                <div class="blue_line"></div>
            </div>
        </div>
        <div class="page-line">
            <div class="text_wrapper">
            <p class="portal_description">Виртуальные миры - это онлайн-университет.<br>
            У нас прикладные курсы и программы от главных экспертов рынка,<br> актуальные подходы к обучению, работа
            над реальными проектами,<br> стажировки и трудоустройство в крупнейшие компании страны.</p>
            </div>
        </div>
        <div class="page-line">
        <div class="page-line__help-frame">
            <div class="page-line__inner-frame">
                <h3>Поможем в выборе!</h3>
                <div class="page-line__p-wrapper">
                <p class="p_light">Если у вас есть вопросы о формате или вы не знаете что выбрать
                 - оставьте свой номер и мы вам позвоним, чтобы ответить на все ваши вопросы.
                </p>
                </div>
                <div class="page-line__name-input-wrapper">
                    <input type="text" name="first_name" placeholder="Имя:">
                </div>
                <div class="page-line__phone-email-input-wrapper">
                    <input type="tel" name="phone_num" placeholder="Телефон:">
                    <input type="email" name="email" placeholder="E-mail:">
                </div>
                <div class="page-line__submit-form-wrapper">
                    <div class="page-line__checkbox-wrapper">
                    <input type="checkbox" name="user_agreement_submit">
                    <label for="send-message">Я согласен с условиями обработки данных</label>
                    </div>
                    <input type="submit" name="send_message" value="Отправить">
                </div>
            </div>
        </div>
        </div>
    </div>     
</body>
</html>
</template>

<style>
  @import 'assets/styles/style.css';
</style>

<script>
export default {
  data() {
    return {
        
        images: {
            telegram: require('@/assets/static/images/telegram.svg'),
            facebook: require('@/assets/static/images/facebook.svg'),
            vk: require('@/assets/static/images/vk.svg'),
            instagram: require('@/assets/static/images/instagram.svg'),
            youtube: require('@/assets/static/images/youtube.svg'),
            uk_flag: require('@/assets/static/images/uk_flag.svg'),
            russian_flag: require('@/assets/static/images/russian_flag.svg'),
            ncfu_logo: require('@/assets/static/images/ncfu_logo.svg'),
            iitt_logo: require('@/assets/static/images/iitt_logo.jpg'),
            logo: require('@/assets/static/images/logo.png'),
        }
    }
  }
}
</script>
